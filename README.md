# Credit Card Fraud Detection with XAI

## Project Overview
This project focuses on detecting credit card fraud using machine learning (ML) and explainable AI (XAI) techniques. With a dataset of 284,807 transactions, we address the challenge of imbalanced data through SMOTE and implement Logistic Regression and XGBoost models. The fine-tuned XGBoost model demonstrates superior performance, achieving 99.97% accuracy and a 98.31% ROC AUC score. SHapley Additive exPlanations (SHAP) is utilized to interpret the model, emphasizing the importance of features like V14, V4, and V12 in fraud detection decisions.

## Key Objectives
- Address the challenge of class imbalance in fraud detection datasets.
- Implement and evaluate Logistic Regression and XGBoost models.
- Enhance model performance through fine-tuning and hyperparameter optimization.
- Apply SHAP for model interpretability, providing insights into feature importance.

## Dataset
The dataset comprises 284,807 credit card transactions, featuring a significant class imbalance with only 0.17% fraudulent transactions. Features include PCA-transformed variables V1 to V28, alongside 'Time' and 'Amount' for transaction details.

## Results
- Logistic Regression: 98.02% accuracy and 96.92% ROC AUC.
- Original XGBoost: 99.94% accuracy and 98.62% ROC AUC.
- Fine-tuned XGBoost: 99.97% accuracy and 98.31% ROC AUC, with improved precision and recall.
