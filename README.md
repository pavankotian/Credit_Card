## Credit Card Fraud Detection

## Project Overview
This project aims to detect fraudulent credit card transactions using machine learning on a highly imbalanced dataset. The focus is on maximizing fraud detection performance using appropriate evaluation metrics rather than accuracy alone.

## Objective
To build a reliable fraud detection model that correctly identifies fraudulent transactions while handling extreme class imbalance.

## Dataset

~284,000 transactions

~492 fraud cases (≈ 0.17%)

Numerical, PCA-transformed features

## Binary target: Fraud / Non-Fraud

## Approach

Feature scaling using StandardScaler

Class imbalance handling using SMOTE

## Models: Logistic Regression, Random Forest

Hyperparameter tuning with RandomizedSearchCV

Threshold tuning to improve fraud recall

## Evaluation Metrics

Precision, Recall, F1-score

Confusion Matrix

ROC-AUC

Precision–Recall Curve

## Key Results

Random Forest with SMOTE achieved the best performance

ROC-AUC ≈ 0.97

Improved recall for fraud detection using lower decision thresholds

## Conclusion
The project demonstrates the importance of imbalance handling, proper metrics, and threshold tuning when building real-world fraud detection systems.

## Author
Pavan Kotian
