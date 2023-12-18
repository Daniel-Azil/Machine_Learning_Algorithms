# Pytorch Implementation of Machine Learning Algorithms.

## 1D-Linear_Regression.ipynb

### Implementation of 1D Linear Regression with PyTorch

#### Overview

This Jupyter Notebook contains a simple implementation of 1D linear regression using PyTorch. The goal is to showcase the process of training a linear regression model with varying learning rates and observing the training and validation errors.

#### Contents

- **Data Generation:** Artificial data is created with outliers, providing both training and validation datasets.
- **Linear Regression Model:** A PyTorch model is defined for 1D linear regression.
- **Training Loop:** The model is trained with different learning rates using stochastic gradient descent.
- **Results:** Training and validation errors are recorded for each learning rate.




## 2-Multiple-Dimension-Linear-Regression.ipynb
### Overview
This Jupyter Notebook (2-Multiple-Dimension-Linear-Regression.ipynb) provides an introduction to building complicated linear regression models using PyTorch. The primary focus is on handling multiple dimensions and understanding the PyTorch functionality for creating, training, and evaluating models.

### Content
#### Objective

Demonstrates how to create complicated models using PyTorch built-in functions.
Preparation

- Imports necessary libraries.
- Sets a random seed.
- Defines a plotting function for 2D visualization.
- Make Some Data

- Creates a dataset class with two-dimensional features.
- Generates a dataset object for training.
- Create the Model, Optimizer, and Total Loss Function (Cost)

- Defines a customized linear regression module.
- Creates a linear regression model with two input features and one output.
- Sets up an optimizer and a loss function.
- Train the Model via Mini-Batch Gradient Descent

- Implements a training function for running Mini-Batch Gradient Descent.
- Plots the model's data performance before and after training.
- Displays a graph of the loss function across iterations.