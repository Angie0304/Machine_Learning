# Multivariate Linear Regression with BGD
This module implements multivariate linear regression using Batch Gradient Descent (BGD) from scratch. It iteratively updates model parameters, tracks estimation error across iterations, and visualizes the convergence behavior of the model.

## Module Structure 

``` text 
preprocessing_and_scaling/
├── README.md                 # Documentation and execution guide
├── bgd_multivariable.ipynb   # Scaling on linear and polynomial regression models
└── requirments.txt           # Dependencies
```

## How it works

The module follows these steps:

1. Load the dataset and split it into training and testing sets
2. Initialize model weights
3. Compute predictions using the linear model
4. Calculate estimation error
5. Update weights using Batch Gradient Descent
6. Repeat for a fixed number of iterations
7. Track error and predictions at each iteration
8. Visualize error convergence
