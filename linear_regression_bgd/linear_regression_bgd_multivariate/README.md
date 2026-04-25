# Multivariate Linear Regression with BGD
This module implements multivariate linear regression using Batch Gradient Descent (BGD) from scratch. It iteratively updates model parameters, tracks estimation error across iterations, and visualizes the convergence behavior of the model.

## Module Structure 

``` text 
preprocessing_and_scaling/
├── README.md                 # Documentation and execution guide
├── bgd_multivariable.ipynb   # Multivariate linear regression using BGD
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

## Usage

1. Install dependencies

```bash
pip install -r requirements.txt
```

2. Run the notebook
```bash
python linear_regression_bgd_multivariate.py
```

3. Output

The program will:

- Show updated weights at each iteration  
- Track estimation error across iterations  
- Display predictions on test data  
- Visualize error convergence


## Dataset 
The dataset used in this module was provided as part of a Machine Learning course and is not included in this repository. The code can be adapted to any tabular dataset containing multiple input features and a target variable for multivariate linear regression.

## Status 
Complete
