Customer Churn Prediction (Machine Learning)
📖 Project Overview

Customer Churn Prediction is a Machine Learning project to predict whether a customer will leave the company (Churn = Yes) or stay (Churn = No) based on customer details like contract type, monthly charges, tenure, and services used.

This helps companies to identify customers who are likely to leave and take actions like giving offers or better support.

🎯 Problem Statement

Build a model that predicts customer churn using historical customer data.

📂 Dataset

Telco Customer Churn Dataset (Kaggle)
Dataset contains customer information such as:

tenure

MonthlyCharges

TotalCharges

Contract type

Internet service

Payment method
Target column: Churn (Yes/No)

🛠 Tools & Technologies Used

Python

Google Colab

Pandas, NumPy

Scikit-learn (Logistic Regression)

⚙️ Steps Followed

Loaded dataset from Kaggle in Google Colab

Cleaned the data (handled TotalCharges conversion and missing values)

Converted target column Churn from Yes/No → 1/0

Encoded categorical columns using get_dummies()

Split dataset into Train and Test sets

Trained Logistic Regression model

Evaluated model using Accuracy, Confusion Matrix, Classification Report

📊 Model Performance

Model Used: Logistic Regression
Accuracy: ~78.7%

Example Output:

Accuracy: 0.787

Confusion Matrix and Classification Report included in notebook

▶️ How to Run

Open the notebook file:
Customer_Churn_Prediction.ipynb

Run all cells in Google Colab

✅ Final Result

The model predicts whether a customer will churn or not, helping businesses reduce customer loss and improve retention.

👩‍💻 Author

Abinaya S
