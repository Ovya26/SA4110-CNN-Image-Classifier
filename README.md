__A Convolutional Neural Network (CNN) image classifier__

This project built in Python using PyTorch to automatically categorize images into predefined classes. This project demonstrates the complete workflow of a deep learning application, from raw image data to model deployment.

<u>Key aspects of the project:</u>

__DATA PREPROCESSING__

Handles raw image datasets by resizing, normalizing, and augmenting images to improve model generalization.

Automatically splits data into training, validation, and test sets.

Supports multiple image formats and ensures consistent input shape for the CNN model.

__MODEL ARCHITECTURE__

Uses PyTorch to define a multi-layer convolutional neural network.

Includes convolutional layers for feature extraction, pooling layers for dimensionality reduction, and fully connected layers for classification.

Employs activation functions (ReLU) and dropout layers to prevent overfitting.

__TRAINING & EVALUATION__

Implements efficient training loops with adjustable learning rate, batch size, and number of epochs.

Tracks performance metrics like accuracy and loss during training and validation.

Evaluates the trained model on a test set to provide quantitative performance analysis.

__VISUALIZATION & REPORTING__

Generates plots for training/validation accuracy and loss trends.

Displays sample predictions alongside ground truth labels for qualitative analysis.

Optionally outputs confusion matrices to identify misclassified classes.
