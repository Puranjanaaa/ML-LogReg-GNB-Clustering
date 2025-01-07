# Machine Learning Classification and Clustering Project

This repository contains implementations of various machine learning algorithms applied to two different datasets: customer churn prediction and fish clustering analysis.

## Project Structure
```
ML-LogReg-GNB-Clustering/
├── datasets/
│   ├── Churn_Modelling.csv    # Customer churn dataset
│   └── fish_data.csv          # Fish measurements dataset
├── clustering.ipynb           # Clustering analysis notebook
├── logistic_regression.ipynb  # Logistic regression notebook
└── naive_bayes.ipynb         # Gaussian Naive Bayes notebook
```

## Analysis Overview

### Customer Churn Prediction
Two classification algorithms are implemented to predict customer churn:

1. **Logistic Regression**
   - Binary classification model to predict customer churn
   - Implementation available in `logistic_regression.ipynb`
   - Uses the Churn_Modelling.csv dataset
   - Predicts whether a customer is likely to leave the bank

2. **Gaussian Naive Bayes**
   - Probabilistic classifier based on Bayes' theorem
   - Implementation available in `naive_bayes.ipynb`
   - Uses the same Churn_Modelling.csv dataset
   - Provides probability estimates for churn prediction

### Fish Species Clustering
- Clustering analysis performed on fish measurement data
- Implementation available in `clustering.ipynb`
- Uses fish_data.csv dataset
- Groups fish based on their physical measurements

## Datasets

### Churn_Modelling.csv
- Customer information and churn status
- Features include customer demographics, account information, and banking behavior
- Target variable: Exited/customer churn (Yes/No)

### fish_data.csv
- Fish measurements dataset
- Contains various physical measurements of different fish species
- Used for unsupervised learning (clustering)

## Requirements
- Python 3.x
- Required libraries:
  - numpy
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn
  - jupyter

## Usage

1. Clone the repository
2. Install required dependencies
3. Run Jupyter notebooks in the following order:
   - `logistic_regression.ipynb`
   - `naive_bayes.ipynb`
   - `clustering.ipynb`

## Contributing
Feel free to open issues or submit pull requests for any improvements.

