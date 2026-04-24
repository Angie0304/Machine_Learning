# Scaling Comparison



## Module Structure 
```text
preprocessing_and_scaling/
├── comparación_escalamiento.ipynb  # Feature Scaling: Normalization vs Standardization
├── requirements.txt                # Dependencies
└── README.md                       # Documentation and execution guide
```

## How it works

The module follows these steps:

1. Load and explore the dataset
2. Clean and preprocess the data if necessary
3. Apply Min-Max normalization to rescale features
4. Apply Z-score standardization to normalize distributions
5. Compare the effects of each scaling method
6. Analyze how scaling impacts the data representation


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

- Compare the results of both scaling techniques  
- Visualize the differences between methods

## Dataset 

The dataset used in this project was provided as part of a Machine Learning course and is not included in this repository. The notebook can be adapted to any tabular dataset with numerical features to apply preprocessing and scaling techniques.

## Status 
Complete
