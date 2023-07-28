# Image Classification from Scratch using Deep Learning

## Overview

This codebase contains functions for building and training neural networks for binary image classification (cats vs non-cats). The neural networks are built using deep learning techniques such as forward and backward propagation, gradient descent, and activation functions (sigmoid and ReLU). 

## How to Use

To use the model, follow these steps:

1. Install poetry.
2. Set up the virtual environment with `poetry install`.
3. Run `poetry run run_two` or `poetry run run_four` to execute a script that compares the accuracy with 2 and 4 layers in the neural network.

## Functions

The codebase contains the following functions:

1. `sigmoid`: A function that computes the sigmoid of a given input.
2. `sigmoid_backward`: A function that computes the derivative of the sigmoid function.
3. `relu`: A function that computes the ReLU (rectified linear unit) of a given input.
4. `relu_backward`: A function that computes the derivative of the ReLU function.
5. `linear_forward`: A function that performs a linear forward propagation step.
6. `linear_backward`: A function that performs a linear backward propagation step.
7. `linear_activation_forward`: A function that performs a forward propagation step with activation functions.
8. `linear_activation_backward`: A function that performs a backward propagation step with activation functions.
9. `initialize_parameters`: A function that initializes the parameters of the neural network.
10. `initialize_parameters_deep`: A function that initializes the parameters of a deep neural network.
11. `L_model_forward`: A function that performs forward propagation for a deep neural network.
12. `compute_cost`: A function that computes the cost function for the neural network.
13. `L_model_backward`: A function that performs backward propagation for a deep neural network.
14. `update_parameters`: A function that updates the parameters of the neural network.
15. `two_layer_model`: A function that builds and trains a two-layer neural network.
16. `L_layer_model`: A function that builds and trains a deep neural network.
17. `predict`: A function that predicts the output for a given input.
18. `plot_costs`: A function that plots the cost function over the iterations.
19. `preprocess`: A function that preprocesses the image data.
20. `load_data`: A function that loads the image data from the dataset.

These functions can be used to train a neural network to classify binary images as cats or non-cats. The codebase can be extended to classify other types of images by modifying the `load_data` function to load the appropriate dataset.

## References

Inspired by Andrew Ng's "Neural Networks and Deep Learning" course on Coursera.




