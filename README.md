# Customer Churn Prediction

## Overview
This project predicts whether a customer will churn using machine learning models. The goal is to help businesses identify customers at risk of leaving and take proactive retention actions.

## Dataset
- Telco Customer Churn dataset (~7000 customers)
- Contains demographic, service, and billing information

## Steps Performed
- Data cleaning (handled missing values)
- Feature engineering and encoding
- Exploratory Data Analysis (EDA)
- Model training (Logistic Regression, Random Forest)
- Model evaluation and comparison

## Results
- Logistic Regression Accuracy: ~80%
- Random Forest Accuracy: ~78%
- Logistic Regression performed slightly better

## Key Insight
The churn prediction problem shows relatively linear relationships between features and target, making Logistic Regression effective.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

## How to Run

1. Clone the repository:
   git clone https://github.com/JeevanGowdaGR/customer-churn-prediction.git
   cd customer-churn-prediction
2. Install dependencies:
   pip install pandas numpy scikit-learn
