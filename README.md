# Handwritten-Digit-Recognition
This project demonstrates handwritten digit recognition using Logistic Regression on the MNIST dataset. The goal is to classify handwritten digits (0-9) from images using a simple machine learning model. In this version, we focus on detecting a specific digit (in this case, digit '2') using a binary classification approach.

# Features:
- Logistic Regression Classifier: A Logistic Regression model is used for classification, which is trained to detect a specific digit (in this example, '2').
- MNIST Dataset: The dataset used is the famous MNIST dataset, containing 70,000 28x28 grayscale images of handwritten digits (60,000 for training and 10,000 for testing).
- Binary Classification: The project implements binary classification (detecting whether the digit is '2' or not).
- Cross-Validation: Cross-validation is used to evaluate the model's performance, with accuracy reported on different data splits.
# Workflow:
- Loading the Dataset: The MNIST dataset is fetched using fetch_openml.
- Preprocessing: The data is reshaped and normalized for training. The labels are converted to integers, and a binary target is created for detecting digit '2'.
- Model Training: A Logistic Regression classifier is trained using the training data, and the model is used to predict the class of a sample image.
- Evaluation: Cross-validation is performed to evaluate the model's accuracy.
# Technologies:
- Python
- Scikit-learn: For loading the dataset, training the model, and performing cross-validation.
- Matplotlib: For visualizing the handwritten digits.
- Logistic Regression: Used as the classification model.

# About Dataset
Context
MNIST is a subset of a larger set available from NIST (it's copied from http://yann.lecun.com/exdb/mnist/)

# Content
The MNIST database of handwritten digits has a training set of 60,000 examples, and a test set of 10,000 examples. .
Four files are available:
- train-images-idx3-ubyte.gz: training set images (9912422 bytes)
- train-labels-idx1-ubyte.gz: training set labels (28881 bytes)
- t10k-images-idx3-ubyte.gz: test set images (1648877 bytes)
- t10k-labels-idx1-ubyte.gz: test set labels (4542 bytes)
