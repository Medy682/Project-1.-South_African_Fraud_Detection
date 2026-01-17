South African Fraud Detection Project Using Machine Learning with EDA

Author: Kidima Medy Masuka

Date: 2026

✅ Project Overview

This project explores the application of machine learning techniques for detecting fraudulent transactions within a synthetic dataset designed to reflect realistic transaction behaviour in the South African financial context. The focus is on handling extreme class imbalance, evaluating model performance using appropriate metrics, and ensuring transparency through explainable AI techniques or Explainable AI  with tools like Shap.

✅ Objectives

Investigate the challenges of fraud detection under severe class imbalance

Apply resampling techniques to mitigate minority-class underrepresentation

Evaluate model performance using imbalance-aware metrics

Develop an interpretable, decision-support fraud detection model

Simulate a realistic South African fraud detection use case

✅ Methodology

Exploratory Data Analysis (EDA):
Transaction behaviour analysis, class imbalance inspection, and correlation analysis

Preprocessing:
Encoding, feature scaling, and stratified train–test splitting

Imbalance Handling:
SMOTENC for mixed numerical and categorical feature resampling

Modeling:
XGBoost classifier with hyperparameter optimisation using GridSearchCV

Evaluation:
Confusion Matrix, Precision, Recall, F1-score, ROC-AUC, and Precision–Recall AUC

Explainability:
SHAP for global feature importance and local (transaction-level) explanations

✅ Key Results

Severe class imbalance (≈3% fraud) strongly constrains model performance

High overall accuracy is driven by the correct classification of non-fraud transactions

Fraud recall remains low, even after threshold tuning, highlighting data limitations

ROC-AUC shows limited discriminative power in this imbalanced setting

Precision–Recall AUC provides a more appropriate assessment of minority-class detection

SHAP explanations enhance transparency without overstating predictive capability

⚠️ Limitations

The dataset is synthetic and may not fully capture real-world fraud complexity

Extremely limited fraud samples restrict minority-class generalisation

Threshold tuning alone is insufficient to substantially improve fraud recall


🚀 Future Improvements

Incorporate cost-sensitive learning and business-driven evaluation metrics

Expand feature engineering with behavioural and contextual attributes

Combine machine learning predictions with rule-based fraud detection systems

Implement model monitoring, drift detection, and continuous retraining

Evaluate performance using real-world transaction data where feasible


🛠 Tools Used

Python

Pandas

Scikit-learn

XGBoost

imbalanced-learn (SMOTENC)

SHAP

Matplotlib / Seaborn


👤 Author

Kidima Medy Masuka

Aspiring Data Scientist | Data Analyst 
Focused on data-driven decision-making, risk analytics, and machine learning


Usage & Attribution

This project is shared for educational and portfolio purposes.  
If reused or adapted, appropriate credit must be given to the author.

📰This project is part of my personal data science portfolio ✅

