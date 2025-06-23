# Telco Customer Churn Analysis 📊

This project analyzes customer churn behavior using a real-world telecom dataset. The goal is to uncover actionable insights through data cleaning, transformation, and visualization using Python.

## 🔍 Project Overview

- **Dataset:** Telco Customer Churn (public telecom dataset)
- **Tools used:** Jupyter Notebook, pandas, seaborn, matplotlib
- **Main objective:** Understand why customers leave (churn), identify patterns, and support business decisions with visual insights

## 🧹 Data Cleaning

Key steps in data preprocessing:
- Converted object-type numerical columns to float
- Removed missing values and irrelevant columns
- Created dummy variables for categorical features
- Standardized Yes/No values to binary form
- Added readable labels for customer status (Stayed vs. Churned)

## 📊 Visualizations & Insights

- **Churn Distribution:** Most customers stayed, but monthly contracts showed higher churn.
- **Churn by Gender:** No significant difference between male and female customers.
- **Churn by Contract Type:** Month-to-month contracts had a much higher churn rate.
- **Monthly Charges:** Customers who churn tend to have higher monthly charges.
- **Correlation Heatmap:** Strong negative correlation between tenure and churn.

Each visualization is paired with a business-oriented interpretation.

## 📁 Folder Contents

- `Telco_Customer_Churn_Analysis.ipynb` – the complete Jupyter Notebook
- `.gitignore` – standard Python exclusions
- `README.md` – project description

## ✅ Skills Demonstrated

- Data cleaning and preprocessing with pandas
- Exploratory data analysis (EDA)
- Visual storytelling with seaborn/matplotlib
- Business insight generation from raw data

## 📌 Note

This project is intended as a portfolio piece for showcasing data analysis skills in Python.  
No machine learning was applied in this phase – the focus is on data exploration and insight communication.
