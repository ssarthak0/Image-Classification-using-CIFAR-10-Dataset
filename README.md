Overview
This project involves building an image classification model using Principal Component Analysis (PCA) and Convolutional Neural Network (CNN) algorithms. The goal is to classify images from the CIFAR-10 dataset into 10 different classes with high accuracy.

Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images across 10 classes, with 6,000 images per class. The classes include airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks.

Methodology
Data Preprocessing:

Image normalization: Scaled pixel values to the range [0, 1].
Data augmentation: Applied random transformations to increase training data diversity.
Feature Extraction:

Used Principal Component Analysis (PCA) to reduce dimensionality and extract features.
Extracted relevant features from images for input to the classification model.
Model Training:

Implemented a Convolutional Neural Network (CNN) using TensorFlow and Keras.
Split the dataset into training and testing sets.
Fine-tuned hyperparameters and optimized model performance.
Evaluation:

Evaluated model accuracy, precision, recall, and F1 score on the test dataset.
Achieved an accuracy of 85% on the CIFAR-10 dataset.
Tech Stack
Python 3.x
TensorFlow
Keras
NumPy
Matplotlib (for visualization)
