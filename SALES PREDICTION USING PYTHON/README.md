# Advertising Sales Prediction

This project is part of my internship at **CodSoft** and focuses on building a predictive model to estimate product sales based on advertising expenditure. The objective is to understand how investments in TV, Radio, and Newspaper advertising influence sales and to develop a reliable linear regression model for forecasting.

## Project Overview

Using a well-structured dataset of advertising budgets and corresponding product sales, this project covers:

- Data loading and inspection  
- Exploratory data analysis (EDA)  
- Linear regression modeling  
- Model performance evaluation  
- Interpretation of results to determine feature importance

## Tools and Technologies

- Python 3  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn

## Workflow Summary

### 1. Data Loading  
The dataset (`advertising.csv`) was imported using Pandas, and its structure was reviewed for any missing values or inconsistencies.

### 2. Exploratory Data Analysis  
- Examined the relationship between advertising channels (TV, Radio, Newspaper) and sales  
- Visualized data using scatter plots and correlation matrices  
- Identified strong positive correlations with TV and Radio

### 3. Model Development  
- Split the dataset into training and testing sets  
- Trained a linear regression model using scikit-learn  
- Visualized the regression line and predictions

### 4. Model Evaluation  
- Calculated R² Score and Mean Squared Error (MSE) to assess model accuracy  
- Observed high accuracy for TV and Radio predictors

## Key Insights

- TV and Radio advertising significantly influence product sales  
- Newspaper advertising shows minimal correlation  
- Linear regression provides a strong baseline model for this dataset

## How to Run the Project

1. Clone the repository or download the project files  
2. Open `Advertising.ipynb` using Jupyter Notebook  
3. Run the notebook cells in order to perform data analysis, model training, and evaluation

## Files Included

- `Advertising.ipynb`: Main notebook containing code and analysis  
- `advertising.csv`: Dataset used for model training and testing
