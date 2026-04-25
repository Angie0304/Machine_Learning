# Feature Scaling Impact on Regression Models

This module analyzes the impact of feature scaling techniques on regression models, comparing model performance before and after applying scaling methods.

## Module Structure 

``` text 
preprocessing_and_scaling/
├── README.md                              # Documentation and execution guide
├── impacto_escalamiento_regresion.ipynb   # Scaling on linear and polynomial regression models
└── requirments.txt                        # Dependencies
```

## How it works

The module follows these steps:


1. Load and split the dataset into training and testing sets
2. ⁠Train linear and polynomial regression models without scaling
3. ⁠Apply feature scaling techniques (standard and robust scaling)
4. ⁠⁠Retrain the models using scaled data
5. Evaluate model performance using MSE and R²
6. ⁠Compare the impact of scaling on model performance


## Usage

1.⁠ ⁠Install dependencies

``` bash
pip install -r requirements.txt

```

2.⁠ ⁠Run the notebook
⁠
```
jupyter notebook preprocessing_and_scaling.ipynb

```
3.⁠ ⁠Output

The notebook will:

•⁠  ⁠Compare model performance using MSE and R²  
•⁠  ⁠Analyze the impact of scaling on predictions  

## Dataset 

The dataset used in this project was provided as part of a Machine Learning course and is not included in this repository. The notebook can be adapted to any tabular dataset with numerical features to apply preprocessing and scaling techniques.

## Status 
Complete
