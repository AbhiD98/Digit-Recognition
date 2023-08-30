# MNIST Digit Classification with Neural Network

This repository contains a Python script for building and training a simple neural network using TensorFlow and Keras to perform handwritten digit classification on the MNIST dataset.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Loading and Preprocessing Data](#loading-and-preprocessing-data)
  - [Creating the Neural Network Model](#creating-the-neural-network-model)
  - [Compiling and Training the Model](#compiling-and-training-the-model)
  - [Evaluating the Model](#evaluating-the-model)
  - [Making Predictions](#making-predictions)
  - [Saving the Model](#saving-the-model)
- [Results](#results)
- [Contributions](#contributions)
- [License](#license)

## Introduction

This code demonstrates how to build a basic neural network model using TensorFlow and Keras for the purpose of classifying handwritten digits from the MNIST dataset. The MNIST dataset consists of 28x28 grayscale images of handwritten digits, along with their corresponding labels.

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- NumPy

### Installation

1. Clone this repository:
git clone https://github.com/AbhiD98/mnist-digit-classification.git


## Usage

### Loading and Preprocessing Data

The MNIST dataset is automatically loaded from Keras datasets. The images are normalized to values between 0 and 1 by dividing by 255. The images are also flattened from 2D arrays to 1D arrays.

### Creating the Neural Network Model

A simple neural network model is created using Keras Sequential API. It consists of one dense layer with sigmoid activation, suitable for multiclass classification.

### Compiling and Training the Model

The model is compiled with the Adam optimizer and 'sparse_categorical_crossentropy' loss function. It is then trained on the training data for a specified number of epochs.

### Evaluating the Model

The trained model is evaluated on the testing data to measure its performance.

### Making Predictions

The model is used to make predictions on test data. Predicted probabilities and class predictions are demonstrated.

### Saving the Model

The trained model is saved using the Pickle library. It's recommended to use Keras's built-in model saving methods for better compatibility.

## Results

The results of training and evaluation will be displayed in the console. The model's accuracy and loss metrics are commonly used to assess performance.

## Contributions

Contributions to this repository are welcome! If you find any issues or have improvements to suggest, please feel free to create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
