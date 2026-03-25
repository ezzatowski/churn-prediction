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

* Logistic Regression achieved the highest accuracy (~80% accuracy)
* Key factors influencing churn included:

  * Contract type
  * Monthly charges
  * Customer tenure

---

## Model Performance

| Model               | Accuracy | Precision| Recall | F1 Score|  ROC-AUC |
|-------------------- |----------|----------|--------|----------|---------|
| Logistic Regression | 0.806955 | 0.658385 |0.566845| 0.609195 | 0.841585|
| Random Forest       | 0.786373 | 0.623729 |0.491979| 0.550075 | 0.825081|
| XGBoost             | 0.798439 | 0.649007 |0.524064| 0.579882 | 0.840567|
| LightGBM            | 0.801278 | 0.649682 |0.545455| 0.593023 | 0.834916|
---

## Visualization

<img width="539" height="455" alt="Confusion Matrix" src="https://github.com/user-attachments/assets/9597dd26-d7c9-414f-a7f2-7f8fc6c16221" />

<img width="772" height="435" alt="eature Importance Chart" src="https://github.com/user-attachments/assets/8ceeb39c-6c0b-474e-b350-daf452af3e43" />

---

## ROC Curve Comparison

Models were evaluated using ROC-AUC to compare their ability to distinguish between churners and non-churners.
XGBoost achieved the best overall performance.
<img width="567" height="455" alt="output" src="https://github.com/user-attachments/assets/4c3585d0-fe53-4f79-9855-13bcce84a182" />


---

## Business Insights

- Customers on month-to-month contracts have significantly higher churn risk
- High monthly charges combined with low tenure strongly increase churn probability
- Long-term contracts act as a strong retention mechanism
- Early-stage customers (low tenure) should be targeted with retention campaigns

---

## Advanced Modeling Improvements

* Implemented hyperparameter tuning using GridSearchCV
* Added advanced models (XGBoost) and compared performance
* Optimized classification threshold to improve churn detection (recall)
* Evaluated models using ROC-AUC and precision-recall trade-offs

---

## Project Structure

```
churn-prediction/
 ├── notebook/
 │    └── Telco Customer Notebook.ipynb
 ├── data/
 │    └── churn.csv
 ├── images/
 ├── README.md
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
