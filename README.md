# Credit Card Fraud Detection

## Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques.  
The dataset is highly imbalanced, making it a realistic and challenging classification problem.

The goal is to correctly identify fraudulent transactions while minimizing false negatives, which is critical in real-world financial systems.



## Dataset
- Transactions: 284,807
- Fraud cases: 492
- Legitimate cases: 284,315
- No missing values 
- Strong class imbalance (~0.17% fraud)



## Methods Used
- Logistic Regression
- Random Forest Classifier
- Class Weighting
- SMOTE (Synthetic Minority Oversampling Technique)
- Threshold tuning
- Precision–Recall Curve
- ROC–AUC Curve



## Model Evaluation Metrics
Because accuracy is misleading for imbalanced datasets, the following metrics were emphasized:
- Precision
- Recall
- F1-score
- ROC-AUC



## Key Results
- Random Forest with SMOTE performed the best overall
- Achieved high recall for fraud detection while maintaining strong precision
- ROC-AUC score of ~0.96 indicates good class separability
- Threshold tuning helped balance false positives and false negatives



## Key Insights
- Handling class imbalance is more important than model choice
- Recall is more critical than accuracy for fraud detection
- Ensemble models outperform linear models on this dataset


## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib


## Files in This Repository
- `Credit.ipynb` — Complete analysis and model building notebook
- `README.md` — Project documentation

---

## Author
**Pavan Kotian**  
Machine Learning & Data Science Portfolio Project
