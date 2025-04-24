# Mathematics-for-Machine-Learning-Multivariate-Calculus
# Backpropagation

## Overview

This assignment focuses on training a neural network using the backpropagation algorithm to approximate a curve. The network takes a single input (the progress along the curve from 0 to 1) and produces two outputs (the 2D coordinates of points on the curve).

## Network Architecture

The neural network used in this assignment has the following architecture:

-   **Input Layer:** 1 node
-   **Hidden Layer 1:** 6 neurons
-   **Hidden Layer 2:** 7 neurons
-   **Output Layer:** 2 nodes

## Implementation Details

The task involves completing functions to calculate the Jacobian of the cost function with respect to the weights and biases of the network. The implementation is part of a stochastic steepest descent algorithm used for training.

### Key Concepts

-   **Activation Function:** The logistic function (`sigma`) is used.
-   **Feed-forward:** The process of calculating activations in the network.
-   **Backpropagation:** Calculating the gradients of the cost function with respect to the network's parameters.
-   **Jacobian Matrix:** A matrix of all first-order partial derivatives of a vector-valued function.
-   **Cost Function:** A measure of how well the neural network performs.
