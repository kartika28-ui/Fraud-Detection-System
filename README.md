# Fraud-Detection-System
Predict whether a transaction is fraudulent or genuine using trained ML model.

<img src="https://github.com/kartika28-ui/Fraud-Detection-System/blob/main/fraud-detection.png" width="700"/> 

## Deployed Link: https://fraud-detection-kartika28-ui.streamlit.app/

## Power BI Dashboard on Fraud Detection Analysis
<img src="https://github.com/kartika28-ui/Fraud-Detection-System/blob/main/fraud-detection-dashboard.jpeg" width="700">

## Table of Contents

- [Tech Stack](#tech-stack-)
- [Features](#features-)
- [Project Structure](#project-structure-)
- [References & Acknowledgments](#references--acknowledgments-)


## Tech Stack

### Frameworks / Libraries
- **Python 3.10+**
- **Streamlit** – for building interactive frontend
- **scikit-learn** – for ML model building and prediction
- **Joblib** – for loading serialized ML models
- **NumPy & Pandas** – for data manipulation and feature engineering
- **Matplotlib & Seaborn** – for visualization during model evaluation
- **Imbalanced-learn (SMOTE)** – for handling class imbalance during training


## Features

- Predicts whether a financial transaction is **Fraudulent or Genuine** in real-time
- Works with **CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER** transaction types
- Automatically detects **balance anomalies** and flags fraud based on rules
- Implements **Random Forest classifier** for accurate predictions
- Clean, responsive interface using Streamlit
- Lightweight — runs in the browser, no complex setup required
- Deployable to **Streamlit Cloud** or local server
- Provides **fraud probability** along with prediction
- Handles **imbalanced datasets** using SMOTE
- Includes visualizations for model evaluation: Confusion Matrix, Feature Importance


## Project Structure

Fraud-Detection-System
- `fraud_detection_app_streamlit.py`  – Streamlit frontend + prediction logic  
- `fraud_detection.pkl`              – Trained Random Forest ML model  
- `requirements.txt`                 – Project dependencies  
- `README.md`                         – Project documentation  
- `Power BI Dashboard`                - Power BI Dashboard


## References & Acknowledgments

- Inspired by common **financial fraud detection case studies**
- [Scikit-learn documentation](https://scikit-learn.org/stable/documentation.html)  
- [Streamlit documentation](https://docs.streamlit.io/)  
- Tutorials on **handling imbalanced datasets with SMOTE**
- Open-source contributions for **Random Forest tuning and feature engineering**
