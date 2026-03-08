# DigitVision-Handwritten-Digit-Recognition-using-CNN

# Project Overview

This project implements a Handwritten Digit Recognition System using a Convolutional Neural Network (CNN). 

The model is trained to recognize handwritten digits from 0–9 using the MNIST Dataset.

The system learns patterns from handwritten digit images and predicts the correct digit with high accuracy.

This project demonstrates fundamental concepts of Deep Learning, Computer Vision, and Neural Networks.

# Dataset

This project uses the MNIST Dataset, a standard dataset for image classification tasks.
# Dataset details:

Total images: 70,000

Training images: 60,000

Testing images: 10,000

Image size: 28 × 28 pixels

Image type: Grayscale

Classes: Digits 0 – 9

Each image represents a handwritten digit.

# Technologies Used

Python

NumPy

Matplotlib

TensorFlow

Keras

Jupyter Notebook

# Project Workflow

## The project follows the typical Deep Learning pipeline:

1. Import Libraries

Required libraries such as NumPy, Matplotlib, TensorFlow, and Keras are imported.

2. Load Dataset

The MNIST dataset is loaded using Keras built-in dataset utilities.

3. Data Preprocessing

Pixel values normalized from 0–255 → 0–1

Images reshaped to fit CNN input format.

4. Build CNN Model

A Convolutional Neural Network architecture is created consisting of:

Convolution Layers

Max Pooling Layers

Flatten Layer

Dense Layers

Softmax Output Layer

5. Compile Model

The model is compiled using:

Optimizer: Adam

Loss Function: Sparse Categorical Crossentropy

Metric: Accuracy

6. Train Model

The CNN is trained using the training dataset for multiple epochs.

7. Evaluate Model

Model performance is evaluated using the test dataset.

8. Prediction

The trained model predicts the digit from unseen images.


# Typical results:

Training Accuracy: ~98%

Test Accuracy: ~97–99%

The CNN model successfully recognizes handwritten digits with high accuracy.
