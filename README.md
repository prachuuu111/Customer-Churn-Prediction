# Customer Churn Prediction

## Project Description

This project predicts whether a customer is likely to leave (churn) a telecom service using Machine Learning.

The project uses data preprocessing, feature engineering, SMOTE for handling class imbalance, and XGBoost for prediction. A Streamlit web application is also developed to make predictions interactively.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SMOTE
- Joblib
- Streamlit

## Machine Learning Model

The project uses:

- XGBoost Classifier
- SMOTE (Synthetic Minority Over-sampling Technique) for handling class imbalance

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Handling Class Imbalance using SMOTE
6. Train-Test Split
7. Model Training using XGBoost
8. Model Evaluation
9. Model Saving using Joblib
10. Streamlit Deployment

## Features

The model analyzes customer information and predicts the probability of customer churn.

The Streamlit application provides an interactive interface where users can enter customer details and get a churn prediction.

## Project Structure

```text
Customer-Churn-Prediction/
│
├── app.py
├── customer_churn_prediction.ipynb
├── Telecom_Customer_Churn_Prediction.csv
├── customer_churn_xgboost.pkl
├── model_features.pkl
├── requirements.txt
├── .gitignore
└── README.md