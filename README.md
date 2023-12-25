# Pytorch Implementation of Machine Learning Algorithms.

## 1-One_Dimension_Linear_Regression_Training.ipynb

### Implementation of 1D Linear Regression with PyTorch

#### Overview

This Jupyter Notebook contains a simple implementation of 1D linear regression using PyTorch. The goal is to showcase the process of training a linear regression model with varying learning rates and observing the training and validation errors.

#### Contents

- **Data Generation:** Artificial data is created with outliers, providing both training and validation datasets.
- **Linear Regression Model:** A PyTorch model is defined for 1D linear regression.
- **Training Loop:** The model is trained with different learning rates using stochastic gradient descent.
- **Results:** Training and validation errors are recorded for each learning rate.




## Linear_Regression_Multiple_Inputs.ipynb

### Linear Regression with Multiple Inputs

#### Overview
Demonstrates the construction of intricate models using PyTorch's built-in capabilities.

#### Contents

Import essential libraries.
- Initialize a random seed for consistency.
- Define a visualization function for 2D plotting.
- Make Some Data:

- Design a dataset class tailored for two-dimensional features.
- Instantiate a dataset object for model training.
- Model & Setup:

- Construct a specialized linear regression module.
- Establish a linear regression model configured for two inputs and one output.
- Configure an optimizer and select a loss function.
- Training via Mini-Batch Gradient Descent:

- Implement a training mechanism using Mini-Batch Gradient Descent.
- Visualize the model's performance pre and post-training.
- Chart the progression of the loss function throughout iterations.
