# 🏦 Bank Customer Churn Prediction using Neural Networks

## 📌 Project Overview
This project is an end-to-end **Customer Churn Prediction System** built using an **Artificial Neural Network (ANN)**.

The application predicts whether a bank customer is likely to **churn** based on customer details such as credit score, geography, gender, age, balance, tenure, salary, and account activity.

The project includes:
- Data preprocessing
- Categorical encoding
- Feature scaling
- ANN model training
- Saved preprocessing artifacts
- Streamlit web application for real-time prediction

---

## 🚀 Features
- Predicts customer churn using ANN
- User-friendly web app built with Streamlit
- Uses saved preprocessing files for inference
- Displays churn probability
- Gives final churn / not churn decision
- Includes dataset and experiment notebook

---

## 🧠 Problem Statement
Customer churn prediction helps banks identify customers who are likely to leave.

By predicting churn early, businesses can:
- improve retention strategies
- reduce customer loss
- increase profitability

This project uses deep learning to estimate churn probability from customer features.

---

## 📥 Input Features
The model takes the following customer details:

- Geography
- Gender
- Age
- Credit Score
- Balance
- Estimated Salary
- Tenure
- Number of Products
- Has Credit Card
- Is Active Member

### Example Input
- Geography = France
- Gender = Female
- Age = 42
- Credit Score = 650
- Balance = 60000
- Estimated Salary = 50000
- Tenure = 5
- Number of Products = 2
- Has Credit Card = 1
- Is Active Member = 1

---

## 📤 Output
The app returns:

1. **Churn Probability**
   - Example: `Churn probability: 0.72`

2. **Prediction**
   - `The customer is likely to churn`
   - or
   - `The customer is not likely to churn`

### Output Meaning
- Probability closer to **0** → customer is less likely to leave
- Probability closer to **1** → customer is more likely to leave

---

## 🏗️ Project Structure

```text
ANN-Classification-Churn/
│
├── Churn_Modelling.csv              # Dataset
├── experiments.ipynb                # Notebook for preprocessing/training
├── app.py                           # Streamlit application
├── model.h5                         # Trained ANN model
├── label_encoder_gender.pkl         # Saved label encoder for gender
├── onehot_encoder_geo.pkl           # Saved one-hot encoder for geography
├── scaler.pkl                       # Saved feature scaler
├── requirements.txt                 # Dependencies
├── README.md                        # Project documentation
└── LICENSE
