# 📊 Telecom Customer Churn Analysis (Python)

This project analyzes telecom customer churn using Python in a single end-to-end Jupyter Notebook.
It includes data cleaning, exploratory data analysis (EDA), visualizations, feature engineering, and churn insights to help understand customer behavior and retention patterns.

## 🚀 Project Contents

Churn_Analysis.ipynb — full end-to-end code

Customer-Churn-Dataset.csv — dataset used for analysis

requirements.txt — dependencies

## 🔍 Key Steps Performed

Cleaned and prepared the telecom dataset (handled missing values, fixed data types).

Performed detailed EDA to understand churn patterns and customer behavior.

Created visualizations (heatmaps, KDE plots, boxplots, categorical comparisons).

Engineered features using encoding and scaling techniques.

Identified major churn drivers such as:

Short tenure

Month-to-month contracts

Higher monthly charges

Lack of tech support / online security

## 📈 Key Insights

Customers on month-to-month contracts have the highest churn rate.

Customers with higher monthly charges are more likely to leave.

Churn is significantly higher among low-tenure customers.

Value-added services (tech support, online security) lower churn risk.

## 🛠️ How to Run

Clone the repository

Install dependencies

Open the notebook

pip install -r requirements.txt
jupyter notebook

## 📦 Requirements
pandas
numpy
seaborn
matplotlib
scikit-learn
xgboost
shap
joblib
