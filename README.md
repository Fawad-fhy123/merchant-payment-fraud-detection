# AI-Based Merchant Payment Fraud Detection

## Overview
This project builds a machine learning system to detect fraudulent transactions in merchant payment networks.  
It is inspired by real-world fintech systems used by payment processors and banks, simulating a **real-time fraud detection workflow**.

## Motivation
Fraud detection is a critical component of merchant payment services.  
Early detection of suspicious transactions helps minimize financial losses and protect customers.

## Technologies
- **Python**  
- **Pandas, NumPy** for data manipulation  
- **Scikit-learn** for machine learning models  
- **Matplotlib, Seaborn** for visualization  
- **Jupyter Notebook / Google Colab** for experimentation  

## Dataset
Dataset used: Credit card/transaction fraud dataset from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## Models Implemented
- Logistic Regression  
- Random Forest  
- Isolation Forest (anomaly detection)  

## Workflow
1. **Data Exploration** – Understand transaction patterns and fraud distribution  
2. **Data Preprocessing** – Handle missing values, normalize amounts, encode categorical variables  
3. **Feature Engineering** – Create transaction velocity, average transaction value, and merchant-based features  
4. **Model Training** – Train ML models on labeled data  
5. **Model Evaluation** – Use precision, recall, F1-score, and confusion matrices  
6. **Error Analysis** – Identify misclassifications and analyze patterns for improvement  

## Key Insights / Error Analysis
- False positives mostly occur with unusually high-value transactions that are legitimate.  
- Model performance improves with features such as merchant reputation and historical transaction behavior.  
- Demonstrates the importance of feature engineering in real-world payment fraud detection.

## Future Improvements
- Incorporate merchant risk scoring  
- Real-time transaction scoring simulation  
- Expand features with geolocation and customer behavior analysis
