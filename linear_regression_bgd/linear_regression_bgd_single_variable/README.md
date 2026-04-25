# Single-Variable Linear Regression with BGD

This module implements single-variable linear regression using Batch Gradient Descent (BGD) from scratch. It iteratively updates the model parameter, tracks estimation error, and visualizes both the regression fit and error convergence across iterations.

## Module Structure 

``` text 
preprocessing_and_scaling/
├── README.md                 # Documentation and execution guide
├── bgd_monovariable.ipynb    # Single-variable linear regression using BGD
└── requirments.txt           # Dependencies
```
## How it works

The module follows these steps:

1. Load the dataset and split it into training and testing sets
2. Initialize the model weight
3. Compute predictions using the linear model
4. Calculate estimation error
5. Update the weight using Batch Gradient Descent
6. Repeat for a fixed number of iterations
7. Track predictions and error at each iteration
8. Visualize regression lines and error convergence

## Usage 

1. Install dependencies

```bash
pip install -r requirements.txt
```

2. Run the notebook
```bash
jupyter notebook bgd_monovariable.ipynb
```

3. Output
The notebook will:
- Show updated weight at each iteration
- Display predictions on test data
- Visualize regression lines and error convergence

## Dataset 
The dataset used in this module was provided as part of a Machine Learning course and is not included in this repository. The code can be adapted to any tabular dataset containing a single input feature and a target variable for linear regression.

## Status 
Complete
