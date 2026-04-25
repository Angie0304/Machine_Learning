# Regression Analysis with OLS and SGD
This module implements linear and polynomial regression models using OLS and SGD, comparing their performance across different configurations.

## Module Structure 

``` text 
preprocessing_and_scaling/
├── README.md                       # Documentation and execution guide
├── comparacion_ols_vs_sgd.ipynb    # OLS vs SGD regression comparison
└── requirments.txt                 # Dependencies
```

## How it works 

The module follows these steps:

1. Load and split the dataset
2. Train linear regression (OLS)
3. Train polynomial models (degree 2 and 3)
4. Evaluate performance (MSE, R²)
5. Set SGD parameters
6. Train models using SGD
7. Compare results
8. Visualize predictions


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
The dataset used in this project was provided as part of a Machine Learning course and is not included in this repository. The notebook can be adapted to any tabular dataset with numerical features to train and evaluate regression models.

# Status 
Complete 
