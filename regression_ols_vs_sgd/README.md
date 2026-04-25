# Regression Analysis with OLS and SGD
This module implements linear and polynomial regression models using Ordinary Least Squares (OLS) and Stochastic Gradient Descent (SGD), comparing their performance across different configurations.

## Module Structure 

``` text 
preprocessing_and_scaling/
├── README.md                       # Documentation and execution guide
├── comparacion_ols_vs_sgd.ipynb    # OLS vs SGD regression comparison
└── requirments.txt                 # Dependencies
```

## How it works 

The module follows these steps:

1. Load the dataset and split it into training and testing sets
2. Train linear regression OLS
3. Train polynomial regression models (degree 2 and 3) using OLS
4. Evaluate model performance using MSE and R²
5. Define SGD parameters (number of iterations and learning rate)
6. Train linear and polynomial regression models using SGD
7. Compare results across models and optimization methods
8. Visualize predictions against actual data


## Usage

1. Install dependencies

```bash
pip install -r requirements.txt
```

2. Run the notebook
```bash
jupyter notebook comparacion_ols_vs_sgd.ipynb
```
3. Output

The notebook will:

- Analyze differences between OLS and SGD  
- Visualize predictions against actual data

# Dataset 
The dataset used in this module was provided as part of a Machine Learning course and is not included in this repository. The notebook can be adapted to any tabular dataset with numerical features to train and evaluate regression models.

# Status 
Complete 
