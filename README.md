# Customer Churn Prediction - ML Pipeline

## 📌 Project Overview

This project demonstrates an **end-to-end Machine Learning Pipeline** for predicting customer churn using the Telco Customer Churn dataset.
The goal is to build a **reusable, scalable, and production-ready ML workflow** using Scikit-learn's Pipeline API.

The pipeline automates data preprocessing, model training, hyperparameter tuning, and model export, making it suitable for real-world deployment scenarios.

---

## 🎯 Objective

* Predict whether a customer will churn or not.
* Build a reusable ML pipeline.
* Apply preprocessing and modeling in a single workflow.
* Implement hyperparameter tuning using GridSearchCV.
* Export the trained pipeline for production use.

---

## 📊 Dataset

**Dataset Used:** Telco Customer Churn Dataset (Kaggle)

Features include:

* Customer demographics
* Account information
* Services subscribed
* Billing details
* Churn status (Target Variable)

Target Variable:

* `Churn` → Yes / No

---

## ⚙️ Technologies Used

* Python
* Pandas & NumPy
* Scikit-learn
* Pipeline API
* ColumnTransformer
* Logistic Regression
* Random Forest Classifier
* GridSearchCV
* Joblib

---

## 🧠 Machine Learning Workflow

### 1️⃣ Data Preprocessing

* Removed unnecessary columns
* Handled missing values
* Converted data types
* Feature scaling using StandardScaler
* Categorical encoding using OneHotEncoder

### 2️⃣ Pipeline Construction

Used Scikit-learn Pipeline to combine:

* Preprocessing
* Model training

### 3️⃣ Models Implemented

* Logistic Regression
* Random Forest Classifier

### 4️⃣ Hyperparameter Tuning

* GridSearchCV applied for optimal model performance.

### 5️⃣ Model Evaluation

* Accuracy Score
* Classification Report

### 6️⃣ Model Export

Final trained pipeline saved using **joblib** for reuse.

---

## 💾 Load Saved Model

```python
import joblib

model = joblib.load("churn_pipeline.pkl")
prediction = model.predict(sample_data)
```

---

## 📈 Skills Gained

* ML Pipeline Construction
* Feature Engineering Automation
* Hyperparameter Tuning
* Model Reusability
* Production-ready ML Practices


## 🌟 Key Highlights

✔ End-to-End ML Workflow
✔ Automated Preprocessing
✔ Multiple Model Training
✔ GridSearch Optimization
✔ Production-Ready Pipeline

