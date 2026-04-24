# Feature Scaling Impact on Regression Models



## Module Structure 
```text
preprocessing_and_scaling/
├── README.md                        # Documentation and execution guide
├── requirements.txt                 # Dependencies
└── scaling_impact_regression.ipynb  # Scaling on linear and polynomial regression models
```

## How it works

The module follows these steps:

1. Load and split the dataset into training and testing sets
2. Train linear and polynomial regression models without scaling
3. Apply feature scaling techniques (standard and robust scaling)
4. Retrain the models using scaled data
5. Evaluate model performance using MSE and R²
6. Compare the impact of scaling on model performance


## Usage

1. Install dependencies

```bash
pip install -r requirements.txt
```

2. Run the notebook
```bash 
jupyter notebook preprocessing_and_scaling.ipynb
```

3. Output

The notebook will:

- Compare model performance using MSE and R²  
- Analyze the impact of scaling on predictions  

## Dataset 

The dataset used in this project was provided as part of a Machine Learning course and is not included in this repository. The notebook can be adapted to any tabular dataset with numerical features to apply preprocessing and scaling techniques.

## Status 
Complete
