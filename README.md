# Customer Churn Prediction

## Overview
This project predicts whether a customer will churn using machine learning models.

## Dataset
- Size: 5000+ records
- Features: Customer demographics, usage patterns, account info

##  Models Used
- Logistic Regression
- Random Forest

##  Results
- Logistic Regression Accuracy: 82%
- Random Forest Accuracy: 86%
- ROC-AUC Score: 0.88

## Key Insights
- Customers with low engagement have higher churn probability
- Monthly charges significantly impact churn

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

##  How to Run
```bash
pip install -r requirements.txt
python churn_model.py
