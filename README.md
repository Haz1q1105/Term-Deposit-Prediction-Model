# Term-Deposit-Prediction-Model
## Overview
This project analyzes the **Bank Marketing dataset** to predict whether a customer will subscribe to a term deposit.  
Used **Logistic Regression** and **Random Forest** as classifiers, evaluate their performance, and apply **LIME** for determining the reason behind model behaviour

## Dataset
- Source: Bank Marketing dataset (UCI Repository)
- Target variable: `y` (yes/no for term deposit subscription)

## Models Used
1. Logistic Regression
2. Random Forest

## Evaluation Metrics
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

## Feature Importance
- Random Forest feature importance ranking
- LIME used to explain individual predictions 

## Results
- Logistic Regression and Random Forest compared on metrics
- Random Forest performed slightly better overall
- ROC-AUC was around 95%
- Key feature was **duration**, **balance**

## Explainability
- LIME was used to explain 5 individual predictions.
- Example: A short call duration and low balance strongly contributed to predicting "No".

## Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- LIME (successfully implemented for local explanations)
- Jupyter Notebook

