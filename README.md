# Neural Network Depth Analysis : How the Number of Hidden Layers Affects Learning

## Overview

This project explores how the depth of a neural network (i.e., the number of hidden layers) affects its ability to learn complex patterns.

We compare multiple neural network architectures with different depths and analyse their performance using a nonlinear classification dataset.

## Objectives

- Understand how neural network depth impacts learning
- Compare shallow vs deep networks
- Visualise decision boundaries
- Analyse model performance, training time, and complexity

## Dataset

We use a synthetic dataset generated using `make_moons` from scikit-learn.

This dataset is nonlinear and is ideal for demonstrating how deeper neural networks learn more complex decision boundaries.

## Models Used

We trained three models:

- Model 1: 1 hidden layer
- Model 2: 2 hidden layers
- Model 3: 4 hidden layers

All models use:

- ReLU activation (hidden layers)
- Sigmoid activation (output layer)
- Adam optimizer

## Results

The results show that:

- Deeper networks achieve higher accuracy
- Deeper networks learn more complex decision boundaries
- Increasing depth increases computational cost (time and parameters)

## Visualisations

The notebook includes:

- Dataset visualization
- Training accuracy and loss curves
- Decision boundary plots
- Accuracy vs depth graph
- Training time and model complexity comparison

## Reproducibility

To ensure reproducibility, a fixed random seed (`SEED = 42`) is used across:

- NumPy
- TensorFlow
- Dataset generation
- Train-test split

## How to Run

### 1. Install dependencies

```bash
pip install numpy matplotlib scikit-learn tensorflow


## About

This project systematically investigates the impact of neural network depth on learning complex, non-linear patterns using the scikit-learn make_moons dataset. We compare shallow (1 hidden layer), moderate (2 hidden layers), and deep (4 hidden layers) networks, analyzing their performance, decision boundaries, training time, and susceptibility to overfitting. The results highlight the crucial trade-offs between model complexity and generalization capability.
