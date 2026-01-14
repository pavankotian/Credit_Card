# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning techniques on a highly imbalanced real-world dataset.

## Objective
To build a reliable fraud detection model that maximizes fraud recall while keeping false positives low.

## Dataset
- Total transactions: 284,807
- Fraud cases: 492
- Legitimate cases: 284,315
- No missing values
- Highly imbalanced classification problem

## Techniques Used
- Exploratory Data Analysis
- Feature scaling with StandardScaler
- Class imbalance handling using SMOTE
- Logistic Regression (baseline)
- Random Forest Classifier
- Hyperparameter tuning using RandomizedSearchCV
- Evaluation using ROC-AUC, Precision, Recall, and Confusion Matrix

## Model Performance (Final Random Forest)
- ROC-AUC: **0.968**
- Fraud Precision: **~0.93**
- Fraud Recall: **~0.82**
- Very low false positives with strong fraud detection capability

## Key Insights
- Handling class imbalance is critical for fraud detection
- Random Forest significantly outperformed Logistic Regression
- Threshold tuning allows control over fraud recall vs false positives
- ROC-AUC proved to be the most reliable evaluation metric

## Files in This Repository
- `Credit_card_fraud_analysis.ipynb` — Complete analysis and model development
- `README.md` — Project overview and results

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn, Matplotlib, Seaborn

## Author
**Pavan Kotian**
