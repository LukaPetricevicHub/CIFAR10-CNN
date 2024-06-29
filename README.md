# CIFAR-10 Image Classification

## Overview
This project demonstrates a convolutional neural network (CNN) for image classification using the CIFAR-10 dataset. The model is implemented using TensorFlow and Keras, and it achieves a reasonable accuracy in classifying images into one of ten categories.

## Features
- Loads and preprocesses the CIFAR-10 dataset.
- Builds a CNN with multiple convolutional and pooling layers.
- Compiles the model with Adam optimizer and Sparse Categorical Crossentropy loss function.
- Trains the model and evaluates its performance on test data.
- Prints the test accuracy.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/YourUsername/YourRepository.git
    cd YourRepository
    ```
2. Install the required packages:
    ```bash
    pip install tensorflow matplotlib
    ```

## Usage
1. Run the script to train the model and evaluate its performance:
    ```bash
    python cifar10_classification.py
    ```
    

## Acknowledgments
This project uses the CIFAR-10 dataset provided by the [TensorFlow Datasets](https://www.tensorflow.org/datasets/catalog/cifar10).
