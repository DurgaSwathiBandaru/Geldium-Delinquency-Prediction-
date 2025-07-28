![Status](https://img.shields.io/badge/Project-Geldium%20Delinquency%20Prediction-blue) ![License](https://img.shields.io/badge/License-MIT-green)

# Credit Card Delinquency Prediction – Geldium (Tata iQ)

This project predicts whether a customer is likely to become delinquent on their credit card payments. Built during the Tata iQ x Forage simulation, it aims to support the Collections team with early risk identification.

---

## Problem Statement

Identify risky credit card customers using financial behavior and help the Collections team prioritize outreach.

---

## Approach

- **EDA**: Analyzed distributions, patterns, and class imbalance  
- **Feature Engineering**: Encoded categories, created average payment score  
- **Modeling**: Logistic Regression, Random Forest, XGBoost  
- **Imbalance Handling**: SMOTE for class balancing  
- **Evaluation**: Accuracy, ROC AUC, Confusion Matrix, Classification Report  
- **Visualization**: PCA, feature importance, payment behavior trends

---

## Key Results

-  **Random Forest**: 90.4% Accuracy, 0.90 AUC  
-  **XGBoost**: 89.2% Accuracy, 0.89 AUC  
-  **Logistic Regression**: 51.7% Accuracy (poor performance due to class imbalance)

---

## Tools & Libraries

- Python, Jupyter Notebook  
- pandas, numpy, seaborn, matplotlib  
- scikit-learn  
- imbalanced-learn (SMOTE)  
- XGBoost

---

## Dataset

`Delinquency_prediction_dataset.xlsx`  
Simulated customer behavior data including monthly payment history, income, card type, and delinquency status.

