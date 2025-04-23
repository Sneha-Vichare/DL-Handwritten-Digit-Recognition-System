**Handwritten Digit Recognition**

Overview
This project demonstrates the application of deep learning for handwritten digit recognition using the popular MNIST dataset. 
By leveraging Python, Keras, and Jupyter Notebook, a convolutional neural network (CNN) model is trained to classify digits (0-9) with high accuracy. 
This project is ideal for beginners in deep learning and computer vision.

Features
Dataset: Utilizes the MNIST dataset containing 60,000 training images and 10,000 testing images of handwritten digits.
Preprocessing: Includes normalization of pixel values and one-hot encoding of labels.
Model Architecture: Implements a CNN with layers such as convolution, max-pooling, dropout, and dense.
Training: Tracks loss and accuracy using a visual progress chart.
Evaluation: Validates the model's performance using the test dataset.
Visualization: Includes visualization of digit samples and prediction results.

Data Loading: MNIST dataset is loaded using Keras's built-in dataset module.
Data Preprocessing: Pixel values are normalized, and labels are converted to categorical data.
Model Definition: A CNN model is defined with appropriate layers.
Model Training: The model is trained using the training dataset and validated on the test dataset.
Evaluation and Prediction: The trained model is evaluated for accuracy and tested on unseen data.
