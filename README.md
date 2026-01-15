Credit Card Fraud Detection
Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques.
Due to the highly imbalanced nature of fraud data, special attention is given to model selection, evaluation metrics, and threshold tuning rather than relying on accuracy alone.

The goal is to build a practical fraud detection system that prioritizes catching fraudulent transactions while maintaining reasonable false alarm rates.

Objective

To identify fraudulent transactions accurately by handling extreme class imbalance and optimizing models using appropriate evaluation metrics such as ROC-AUC, precision, and recall.

Dataset Summary

Total transactions: ~284,000

Fraud cases: ~492 (≈ 0.17%)

Features: PCA-transformed numerical variables + transaction amount

Target: Fraud (1) vs Non-Fraud (0)

Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Imbalanced-learn (SMOTE)

Matplotlib / Seaborn

Methodology
1. Data Preprocessing

Feature scaling using StandardScaler

Train–test split

Handling class imbalance

2. Models Implemented

Logistic Regression (baseline)

Random Forest Classifier

3. Imbalance Handling Techniques

Class weights

SMOTE (Synthetic Minority Oversampling Technique)

4. Model Optimization

Hyperparameter tuning using RandomizedSearchCV

ROC-AUC used as the scoring metric

5. Model Evaluation

Confusion Matrix

Precision, Recall, F1-score

ROC-AUC score

Precision-Recall Curve

Decision threshold tuning

Key Results

Random Forest + SMOTE significantly outperformed baseline models

ROC-AUC ≈ 0.97, indicating strong ranking ability

Threshold tuning improved fraud recall

Lower thresholds increased recall at the cost of precision — acceptable for fraud detection

Best practical performance achieved around threshold = 0.2

Final Model Choice

Model: Random Forest with SMOTE

Evaluation Focus: Recall, Precision, ROC-AUC

Reasoning:
In fraud detection, missing a fraudulent transaction is more costly than flagging a legitimate one.

Conclusion

This project demonstrates that fraud detection systems require careful metric selection and imbalance handling.
By combining Random Forests, SMOTE, ROC-based evaluation, and threshold tuning, the final model effectively identifies fraudulent transactions in a highly imbalanced dataset.
