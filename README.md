# Neural-Network

This task involves creating a neural network library and using it to solve two problems: XOR problem and handwritten digit recognition (MNIST dataset).

## Neural Network Library

Implementing a neural network library consisting of classes for different types of layers (e.g., Linear, Sigmoid, Hyperbolic Tangent, Softmax) and functionalities such as forward and backward passes. It utilizes polymorphism and inheritance for code reusability and organization.

### Layers Implemented:
- `Layer` class: Parent class defining forward and backward functions.
- `Linear` layer: Implements linear transformation.
- `Sigmoid` function: Implements logistic sigmoid activation.
- Hyperbolic Tangent function: Implements hyperbolic tangent activation.
- `Softmax` function: Implements softmax activation.
- Cross-Entropy Loss: Implements cross-entropy loss function.
- `Sequential` class: Contains a list of layers to construct a neural network.

The program implements saving and loading of model weights to/from files.

## Solving XOR Problem

Constructing a neural network with 1 hidden layer of 2 nodes to solve the XOR problem that uses both sigmoid and hyperbolic tangent activations and saved the weights. The `fit_XOR.py` file contains the implementation with a comment describing the hyperparameters used.

## Handwritten Digit Recognition (MNIST)

Utilizing the neural network library to construct multiple networks for handwritten digit recognition on the MNIST dataset. Experimenting with various network configurations and hyperparameters. This uses early stopping based on the validation loss to prevent overfitting.

Training at least 3 different models, plotting the training and validation loss for each configuration and evaluating each model on the test set and reported the test accuracy.
