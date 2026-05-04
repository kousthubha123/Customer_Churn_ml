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
##  Model Performance

| Model | Accuracy | ROC-AUC |
|------|---------|--------|
| Logistic Regression | 82% | 0.85 |
| Random Forest | 86% | 0.88 |

##  Key Insights

- Customers with high monthly charges are more likely to churn
- Long-term contract customers show lower churn rates
- Customers with low engagement are at high risk

##  Visualizations

- Confusion Matrix
- ROC Curve
- Feature Importance Graph
- ## Visualizations

### RFM Analysis
![RFM](images/rfm_analysis.png)

### Top Customers by Revenue
![Revenue](images/revenue_chart.png)

---

##  Business Insights

- Customers with high recency are more likely to churn
- Loyal customers generate maximum revenue
- At-risk customers show declining engagement patterns

---

##  Business Impact

This project helps businesses:
- Identify customers likely to churn
- Improve retention strategies
- Increase revenue through targeted actions
##  How to Run
```bash
pip install -r requirements.txt
python churn_model.py
