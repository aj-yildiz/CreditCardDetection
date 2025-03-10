# CreditCardDetection

Credit Card Fraud Detection

Overview

This project focuses on credit card fraud detection using machine learning techniques. The dataset comes from the Kaggle Credit Card Fraud Detection dataset. The dataset contains anonymized credit card transactions labeled as fraudulent (1) or non-fraudulent (0). Due to extreme class imbalance, specialized techniques such as SMOTE, undersampling, and balanced models were used.

Features

Data Preprocessing:

Normalization and scaling using RobustScaler

Handling class imbalance with SMOTE and random undersampling

Machine Learning Models:

Logistic Regression

Random Forest

Gradient Boosting (XGBoost, GBC)

Support Vector Machine (SVM)

Neural Network (TensorFlow/Keras)

Model Evaluation:

Precision, Recall, F1-score, and ROC-AUC

Handling false positives vs. false negatives

Performance comparison across multiple models

Dataset

Source: Kaggle Credit Card Fraud Dataset

Description: Contains 284,807 transactions, with only 492 fraudulent transactions (~0.172%)

Key Features:

Time: Time elapsed since first transaction

Amount: Transaction amount (scaled)

V1 to V28: Anonymized principal components from PCA

Class: Target variable (0 = Not Fraud, 1 = Fraud)

Installation & Setup

Clone this repository:
