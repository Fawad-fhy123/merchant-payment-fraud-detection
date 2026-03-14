AI-based fraud detection system for merchant payment transactions inspired by real-world fintech risk monitoring.

# AI-Based Merchant Payment Fraud Detection

## Overview
This project builds a machine learning model to detect fraudulent
payment transactions in merchant payment systems.

Fraud detection is a critical component of modern payment networks
and financial infrastructure.

The goal is to identify suspicious transaction patterns using
machine learning techniques.

## Technologies
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset
Credit card fraud dataset from Kaggle.

## Models Used
- Logistic Regression
- Random Forest
- Isolation Forest (anomaly detection)

## Evaluation
The model is evaluated using:

- Precision
- Recall
- Confusion Matrix

## Error Analysis
The model produced false positives for unusually high-value
transactions that were legitimate.

This occurs because high-value payments often resemble fraud
patterns in the dataset.

Future improvements could include:

- merchant reputation scores
- historical merchant behavior
- transaction velocity analysis
