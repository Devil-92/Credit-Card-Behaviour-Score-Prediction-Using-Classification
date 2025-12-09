# Credit Card Behaviour Score Prediction  
Binary Classification | Credit Risk Modelling | Machine Learning

---

## Project Overview  
This project builds a binary classification model to predict whether a customer is likely to default on their credit card payment in the next month.  
The objective is to support financial institutions in identifying high-risk customers while minimizing false negatives, which are critical in credit risk systems.

The workflow includes:
- Exploratory data analysis (EDA)  
- Behaviour-based feature engineering  
- Class imbalance handling  
- Training and comparing multiple models  
- Threshold tuning to align with business risk requirements  
- Generating predictions for an unlabeled dataset  

---

## Problem Statement  
Credit institutions require reliable early warnings of potential defaulters.  
This model predicts the likelihood of default, enabling more informed credit decision-making.

---

## Dataset Description  
The dataset contains behavioural and financial features, including:
- Customer payment history  
- Repayment trends and delays  
- Credit utilization ratios  
- Delinquency indicators  
- Sequential behavioural patterns across multiple months  

---

## Approach

### 1. Exploratory and Behavioural Analysis  
- Examined repayment consistency, utilization patterns, and delinquency streaks  
- Identified key behavioural signals correlated with credit distress  
- Engineered meaningful features, such as utilization ratios and delinquency summaries  

### 2. Class Imbalance Handling  
Applied multiple techniques to ensure adequate representation of the minority (default) class:
- SMOTE oversampling  
- Class weighting  
- Downsampling  

### 3. Model Training  
Trained and evaluated several models:
- Logistic Regression  
- Decision Trees  
- Random Forest  
- XGBoost  
- LightGBM  

Evaluation metrics included:
- F2 Score (primary metric)  
- AUC-ROC  
- F1-score  

### 4. Threshold Tuning  
Adjusted the classification threshold to reflect business-specific risk tolerance, balancing precision and recall for the high-risk class.

---

## Results  
The final model achieved the following key performance metric:

- Validation **F2 Score:** 0.8721  

This score prioritizes recall for the default class, making it suitable for financial risk assessment.
