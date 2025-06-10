# customer-churn-prediction
A machine learning project to predict Telco customer churn using EDA and Random Forest.
# Customer Churn Prediction – Telco Dataset

This project predicts customer churn using machine learning, based on Telco's customer data.

## 📊 Overview

This project explores customer behavior patterns and uses a Random Forest Classifier to predict whether a customer will leave (churn) based on features like monthly charges, contract type, tenure, and more.

## 📁 Dataset

- Source: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Rows: ~7,000
- Features: Gender, SeniorCitizen, Contract, PaymentMethod, MonthlyCharges, Tenure, etc.

## 🧪 Process

- Cleaned and converted data types (e.g., `TotalCharges`)
- Performed Exploratory Data Analysis (EDA) with visualizations
- One-hot encoded categorical features
- Scaled numeric features
- Trained Random Forest Classifier
- Evaluated performance using precision, recall, F1, and confusion matrix

## 🧠 Key Insights

- Customers with **Month-to-month contracts** had the highest churn
- Higher **Monthly Charges** are correlated with increased churn
- Shorter **tenure** (newer customers) are more likely to leave

## 📈 Model Evaluation

- Accuracy: ~ (fill in yours from report)
- F1 Score: (fill in)
- Confusion Matrix included

## 📌 Future Improvements

- Hyperparameter tuning (GridSearchCV)
- Try other models (e.g., Logistic Regression, XGBoost)
- Build Streamlit web app for interactive predictions

## 👨‍💻 Built by

**Wajeeh Qureshi**  
Student @ Rutgers Business School  
Management Information Systems  
