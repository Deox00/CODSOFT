# Titanic Survival Prediction

This project explores and builds a machine learning model to predict passenger survival on the Titanic using historical data. The goal is to understand which factors most influenced survival and train a model that can make predictions based on those features.

## Project Overview

Using the Titanic dataset, we:

- Clean and preprocess the data
- Perform exploratory data analysis (EDA)
- Build a logistic regression model
- Evaluate the model’s performance
- Visualize key insights like survival rate by gender and class

## Technologies & Tools

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn

## Data Cleaning & Preparation

- Removed irrelevant columns: PassengerId, Name, Ticket, Cabin
- Filled missing age values with the mean
- Encoded categorical variables (Sex and Embarked)
- One-hot encoded the Embarked column

## Exploratory Data Analysis

Some interesting insights:

- Women had a higher survival rate than men
- Passengers in 1st class were more likely to survive

Visualizations like bar plots were used to better understand these patterns.

## Model Training

Used Logistic Regression to train a simple yet interpretable classification model:

```python
model = LogisticRegression(max_iter=200)
model.fit(X_train, y_train)
y_pred = model.predict(X_test)
```

Accuracy and classification report were used to assess performance.

## Results

The model gave us decent accuracy and helped identify some key factors for survival. It’s a great starting point for beginners to understand the fundamentals of data science and machine learning.

## How to Run

1. Clone this repository or download the notebook.
2. Ensure you have Jupyter, Python, and the required libraries installed.
3. Open `Titanic.ipynb` and run the cells.
