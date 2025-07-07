# Credit Card Fraud Detection

This project is part of my internship at **CodSoft** and aims to detect fraudulent credit card transactions using machine learning techniques. The project uses a real-world dataset that is highly imbalanced, which provides an opportunity to apply and evaluate models under challenging conditions.

## Project Overview

The dataset contains transactions made by credit cards in September 2013 by European cardholders. It includes 284,807 transactions, of which only 492 are frauds. All features except for 'Time' and 'Amount' have been transformed using PCA due to confidentiality.

Key goals of this project include:

- Understanding and preprocessing imbalanced data  
- Building a robust classification model  
- Evaluating the model with suitable metrics

## Tools and Technologies

- Python 3  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn

## Workflow Summary

### 1. Data Exploration
- Loaded the dataset and inspected feature distributions  
- Checked for missing values and class imbalance

### 2. Data Preprocessing
- Normalized the 'Time' and 'Amount' features  
- Addressed imbalance using undersampling or SMOTE  
- Split data into training and test sets

### 3. Model Development
- Trained models like Logistic Regression or Random Forest  
- Performed cross-validation where necessary

### 4. Model Evaluation
- Evaluated performance using:
  - Confusion matrix  
  - Precision, Recall, F1-score  
  - ROC-AUC curve

## Key Insights

- Accuracy is misleading for imbalanced datasets; precision and recall are more important  
- Fraudulent transactions have distinct patterns that can be captured through appropriate feature scaling and modeling

## How to Run

1. Clone or download this repository  
2. Place the `creditcard.csv` file in the working directory  
3. Open and run the `Credit_Card.ipynb` notebook in Jupyter Notebook

## Files Included

- `Credit_Card.ipynb` – Jupyter notebook containing code and analysis  
- `creditcard.csv` – The dataset used for modeling
