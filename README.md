# Customer Churn Prediction Project

## Overview
This project predicts customer churn using the Telco Customer Churn dataset. 
The goal is to identify customers likely to leave and provide insights to improve retention strategies.

## Dataset
- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- Contains customer demographics, account information, and churn labels.

## Steps
1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training (Logistic Regression, Random Forest)
5. Model Evaluation (Accuracy, Precision, Recall, F1 Score)
6. Dashboard Insights (Power BI/Looker Studio)

## Results
- Logistic Regression Accuracy: ~80%
- Random Forest Accuracy: ~85%
- Key drivers of churn: contract type, tenure, monthly charges

## How to Run
1. Download dataset from Kaggle and place it in the `data/` folder.
2. Open `churn_prediction.ipynb` in Jupyter Notebook or JupyterLab.
3. Run cells step by step to reproduce results.

## Dashboard
Power BI dashboard shows:
- Churn rate by contract type
- Churn vs. monthly charges
- Tenure impact on churn

*(Screenshots/links can be added here if you publish your dashboard)*

## Tech Stack
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Power BI / Looker Studio
