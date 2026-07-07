# Customer-churn-prediction

## Project Overview

Customer churn is a critical challenge for subscription-based businesses. Retaining existing customers is often more cost-effective than acquiring new ones.

This project develops an end-to-end machine learning pipeline to predict whether a customer is likely to churn using the Telco Customer Churn dataset. The project covers the complete data science workflow, including exploratory data analysis, preprocessing, model development, hyperparameter tuning, and model explainability.

---

## Problem Statement

The objective is to build a binary classification model that predicts customer churn and provides actionable business insights to improve customer retention.

Target Variable:

- **Churn**
  - 1 = Customer churned
  - 0 = Customer retained

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

**Number of Records:** 7,043

**Features:** 20

The dataset includes customer demographics, account information, services subscribed, billing details, and churn status.

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

- Data inspection
- Missing value analysis
- Duplicate checking
- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Churn distribution visualization
- Business insights

---

### 2. Data Preprocessing

- Removed unnecessary columns (`customerID`)
- Converted `TotalCharges` to numeric
- Handled missing values
- Encoded target variable
- Train-Test split
- Pipeline-based preprocessing
- One-Hot Encoding
- Feature Scaling

---

### 3. Model Building

The following machine learning models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- LightGBM

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

### 4. Hyperparameter Tuning

Hyperparameter optimization was performed using **Optuna** to improve the performance of the best baseline model.

---

### 5. Model Explainability

Model predictions were interpreted using **SHAP (SH