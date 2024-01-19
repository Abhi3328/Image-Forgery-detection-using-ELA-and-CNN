# Image-Forgery-detection-using-ELA-and-CNN

 Purpose:

The objective of this project is to develop a Convolutional Neural Network (CNN) model for detecting image forgeries, differentiating between real and manipulated images. The project leverages Error Level Analysis (ELA) as a preprocessing step to enhance the discriminative features in the images.
Methodology:

1. Data Collection:
•	Utilize the CASIA dataset, containing authentic and tampered images(spliced and copy-moved images, as well as images affected by post-processing operations such as filtering and blurring), for training and evaluation.
•	Use ELA to preprocess images, enhancing the visual artifacts of manipulation.

2. ELA Preprocessing:
•	Implement the ELA algorithm to highlight error levels in the images.
•	Adjust the ELA parameters such as quality and scaling for optimal results.
•	Integrate ELA preprocessing into the data pipeline.

3. Model Architecture:
•	Design a CNN architecture for image forgery detection.
•	The CNN should take ELA-enhanced images as input.
•	Include convolutional layers, pooling layers, dense layers, and dropout layers for regularization.

4. Data Augmentation:
•	Apply data augmentation techniques to artificially increase the size of the training dataset.
•	Augmentation may include rotation, flipping, and zooming.

5. Model Training:
•	Train the CNN using the preprocessed images.
•	Use a binary classification setup with labels (real/fake).
•	Monitor training progress with validation data and implement early stopping.

6. Model Evaluation:
•	Evaluate the model's performance on a separate validation set.
•	Visualize confusion matrices to understand model behavior.

7. Hyperparameter Tuning:
•	Experiment with hyperparameter tuning to optimize model performance.
•	Adjust learning rates, batch sizes, and network architecture.

8. Interpretability and Visualization:
•	Visualize feature maps and activations to understand what the model learns.
•	Use visualization tools to identify areas of interest in manipulated images.

![image](https://github.com/Abhi3328/Image-Forgery-detection-using-ELA-and-CNN/assets/118369122/96457193-da30-4be7-be7b-6c1ee454373d)


