# CNN MNIST handwritten digits Classification

This project implements a Convolutional Neural Network (CNN) for classifying handwritten digits from the MNIST dataset using PyTorch.

## Project Overview

The project consists of the following steps:
1. Downloading and loading the MNIST dataset.
2. Creating data loaders for batching and shuffling the data.
3. Defining a CNN model for classification.
4. Setting up the optimizer and loss function.
5. Training the model on the training dataset.
6. Evaluating the model on the test dataset.
7. Visualizing a sample prediction.

## Dataset

The MNIST dataset contains 60,000 training images and 10,000 test images of handwritten digits (0-9). Each image is 28x28 pixels in size.

## Requirements

- Python 3.6 or higher
- torch
- torchvision
- matplotlib
