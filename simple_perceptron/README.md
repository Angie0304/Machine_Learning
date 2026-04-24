# Simple Perceptron
This module implements a Simple Perceptron for binary classification using the Iris dataset. It includes data preprocessing, feature selection, and model training, along with the evaluation of predictions on a linearly separable subset of the data.

## Module Structure

```text
simple_perceptron/
├── data/
│   ├── raw/                          # Original dataset
│   │   └── iris.data
│   │
│   └── processed/                    # Preprocessed data and results
│       ├── iris_binario.csv
│       └── predicciones_perceptron.csv
│
├── notebooks/                        # Implementation and preprocessing
│   ├── Perceptron_Simple.ipynb
│   └── Preprocesamiento_Dataset.ipynb
├── README.md                         # Documentation and execution guide
└── requirements.txt                  # Dependencies
```

## How it works
The module follows these steps:

1. Load and filter the Iris dataset for binary classification
2. Preprocess and select input features
3. Initialize perceptron parameters (weights and bias)
4. Iteratively update weights based on classification errors
5. Apply the trained model to generate predictions

## Usage 

1. Install dependencies

```bash
pip install -r requirements.txt
```

2. Run the notebooks
```bash 
jupyter notebook notebooks/Preprocesamiento_Dataset.ipynb
jupyter notebook notebooks/Perceptron_Simple.ipynb
```

3. Output
The notebooks will:

- Preprocess the dataset
- Generate predictions on the processed data
- Save results in the data/processed/ directory

