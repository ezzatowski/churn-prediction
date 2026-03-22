# Customer Churn Prediction

## Overview

This project focuses on building a machine learning model to predict customer churn — whether a customer is likely to leave a service. Churn prediction is a critical problem in industries like telecommunications, where retaining customers is more cost-effective than acquiring new ones.

The goal is to analyze customer data, identify key factors influencing churn, and build a predictive model that can support business decision-making.

---

## Objectives

* Perform data cleaning and preprocessing
* Explore and understand customer behavior
* Train and evaluate machine learning models
* Identify key features driving customer churn
* Generate actionable business insights

---

## Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

## Dataset

* Telco Customer Churn Dataset (Kaggle)
* Contains customer demographics, account information, and service usage

---

## Project Workflow

### 1. Data Preprocessing

* Removed irrelevant columns (e.g., customerID)
* Converted categorical variables using one-hot encoding
* Handled missing values
* Transformed target variable (Churn: Yes/No → 1/0)

---

### 2. Model Building

Two models were implemented and compared:

* **Random Forest Classifier**
* **Logistic Regression**

---

### 3. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision, Recall, F1-score
* Confusion Matrix

---

### 4. Feature Importance

* Identified the most influential features affecting churn
* Helped derive business insights from the model

---

## Results

* Random Forest achieved strong performance (~80% accuracy)
* Logistic Regression provided a solid baseline for comparison
* Key factors influencing churn included:

  * Contract type
  * Monthly charges
  * Customer tenure

---
## Model Performance

* Random Forest Accuracy: 0.78
* Logistic Regression Accuracy: 0.79

---

## Visualization

<img width="539" height="455" alt="Confusion Matrix" src="https://github.com/user-attachments/assets/9597dd26-d7c9-414f-a7f2-7f8fc6c16221" />

## Business Insights

* Customers with higher monthly charges are more likely to churn
* Long-term contracts significantly reduce churn probability
* Early identification of high-risk customers enables targeted retention strategies

---

## Future Improvements

* Hyperparameter tuning for better performance
* Try advanced models (e.g., XGBoost, Gradient Boosting)
* Deploy the model as a web application
* Integrate real-time prediction pipeline

---

## Project Structure

```
churn-prediction/
│── churn_prediction.ipynb
│── churn.csv
│── README.md
```

---

## Key Learnings

* End-to-end machine learning workflow
* Data preprocessing and feature engineering
* Model comparison and evaluation
* Translating technical results into business insights

---

## Author

**Mahmoud Ismail**
📍 Warsaw, Poland
📧 [mahmoudezzatismail@icloud.com](mailto:mahmoudezzatismail@icloud.com)

---

## ⭐ If you found this project useful

Feel free to star the repository and connect with me!
