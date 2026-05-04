#  Customer Retention & Churn Prediction (ML Project)

##  Overview

This project analyzes customer behavior using **RFM (Recency, Frequency, Monetary)** techniques and builds a **Machine Learning model** to predict customer churn.

It combines **data analytics + machine learning**, making it closer to real-world business use cases.

---

##  Objectives

* Identify customer segments based on behavior
* Detect customers likely to churn
* Build a predictive ML model
* Visualize insights for business decisions

---

##  Dataset

* Transactional customer data
* Features include:

  * CustomerID
  * InvoiceDate
  * Quantity
  * UnitPrice

---

##  Workflow

### 1. Data Preprocessing

* Converted date columns
* Created total transaction value
* Cleaned and structured dataset

### 2. RFM Analysis

* **Recency** → Days since last purchase
* **Frequency** → Number of transactions
* **Monetary** → Total spend

### 3. Customer Segmentation

* Best Customers
* Loyal Customers
* At Risk Customers

### 4. Churn Definition

* Customers with high recency are labeled as **Churned**
* Others are **Active**

---

##  Machine Learning Model

* Model Used: **Logistic Regression**
* Features:

  * Recency
  * Frequency
  * Monetary

###  Model Performance

* Accuracy: ~80% (varies with data)
* ROC-AUC Score: Displayed in output

---

##  Visualizations

###  Churn Distribution

![Churn](images/churn.png)

###  ROC Curve

![ROC Curve](images/roc_curve.png)

###  Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

##  Key Insights

* Customers with **high recency** are more likely to churn
* Frequent customers show higher retention
* High-value customers contribute most to revenue

---

##  Business Impact

This project helps businesses:

* Identify at-risk customers
* Improve retention strategies
* Reduce revenue loss
* Make data-driven decisions

---

##  Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

##  How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
python churn_project.py
```

---

##  Output Files

* `roc_curve.png`
* `confusion_matrix.png`
* `churn.png`
* `rfm_output.csv`

---

## Future Improvements

* Use larger real-world datasets
* Try advanced models (Random Forest, XGBoost)
* Deploy using Streamlit / Flask

---

##  Author

**Kousthubha M**
B.Tech AI & ML Student

---
