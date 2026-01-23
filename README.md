# 📌 Customer Churn Prediction (Telco Dataset)

## 📖 Project Overview
This project predicts whether a customer will **churn (leave the service)** or **not churn (stay)** using Machine Learning.

The goal is to help companies **identify high-risk customers early** and take actions like:
- offering discounts
- improving customer support
- reducing customer loss


---

## 🎯 Problem Statement
Build a Machine Learning model that classifies customers into:

- **Churn = 1** → Customer will leave  
- **Churn = 0** → Customer will stay  


---

## 📂 Dataset Information
**Dataset Name:** Telco Customer Churn (Kaggle)

The dataset contains customer information such as:
- `tenure`
- `MonthlyCharges`
- `TotalCharges`
- `Contract`
- `InternetService`
- `PaymentMethod`
- `OnlineSecurity`
- `TechSupport`

✅ **Target Column:** `Churn`


---

## 🛠 Tools & Technologies Used
- **Python**
- **Google Colab**
- **Pandas, NumPy**
- **Matplotlib**
- **Scikit-learn**


---

## 🔍 Steps Followed

### 1️⃣ Data Loading
The dataset was loaded directly in Google Colab using KaggleHub.

### 2️⃣ Data Cleaning
✔ Converted `TotalCharges` to numeric  
✔ Removed missing values  
✔ Converted `Churn` from **Yes/No → 1/0**  
✔ Removed `customerID` column  

### 3️⃣ Exploratory Data Analysis (EDA)
✔ Checked dataset shape and column details  
✔ Visualized churn distribution using a bar chart  

### 4️⃣ Feature Encoding
Categorical values were converted into numeric values using:

- `pd.get_dummies()`

### 5️⃣ Model Training
Two models were trained and compared:

- **Logistic Regression**
- **Random Forest**

### 6️⃣ Model Evaluation
Model performance was evaluated using:

- Accuracy Score  
- Confusion Matrix  
- Classification Report  


---

## 📊 Results

### ✅ Logistic Regression
**Accuracy:** `0.787` (≈ 78.7%)

### ✅ Random Forest
**Accuracy:** `0.785` (≈ 78.5%)

📌 Logistic Regression performed slightly better in this dataset.


---

## 🧠 Interpretability (Feature Importance)
Random Forest Feature Importance was used to understand the most important factors for churn.

### 🔝 Top Important Features
- `TotalCharges`
- `MonthlyCharges`
- `tenure`
- `InternetService_Fiber optic`
- `PaymentMethod_Electronic check`


---

## 📈 Churn Probability (Risk Score)
Instead of only predicting **Yes/No**, the Logistic Regression model also provides churn probability.

Example output:

---

Top 10 churn probabilities:
[0.0056, 0.1242, 0.6838, 0.1126, 0.3617, 0.4456, 0.1305, 0.7569, 0.2173, 0.0183]
---
Interpretation:

0.75 / 0.68 → High churn risk

0.01 / 0.12 → Low churn risk

##▶️ How to Run This Project

Open the notebook in Google Colab

Run all cells from top to bottom

The output will show:

Accuracy

Confusion Matrix

Classification Report

Feature Importance

Churn Probability


---
👩‍💻 Author
---
Abinaya S
---
****
