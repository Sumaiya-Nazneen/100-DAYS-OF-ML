# Day 17 – XGBoost Classification | Bank Customer Churn Prediction 🏦

## 📌 Overview

On Day 17 of my Machine Learning challenge, I implemented **XGBoost Classification** to predict whether a bank customer will **stay or leave the bank**.

The project uses the **Bank Customer Churn Dataset** and demonstrates how XGBoost can be combined with preprocessing techniques such as **One-Hot Encoding, ColumnTransformer, and Pipeline**.

## 🎯 Objective

The objective is to predict the `Exited` value:

* `0` → Customer stays
* `1` → Customer leaves

## 📊 Dataset

**Dataset:** `Bank_Churn.csv`

**Target Variable:** `Exited`

### Features

The dataset contains customer information such as:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Credit Card
* Active Membership
* Estimated Salary

## 🧹 Data Preparation

The following unnecessary columns were removed:

* `RowNumber`
* `CustomerId`
* `Surname`

Categorical columns:

* `Geography`
* `Gender`

These categorical features were converted into numerical features using **OneHotEncoder**.

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* XGBoost

## 🔄 Machine Learning Workflow

```text
Load Dataset
     ↓
Remove Unnecessary Columns
     ↓
Separate Features & Target
     ↓
Identify Categorical Columns
     ↓
One-Hot Encoding
     ↓
Train-Test Split
     ↓
Pipeline
     ↓
XGBoost Classifier
     ↓
Prediction
     ↓
Model Evaluation
```

## ⚙️ Preprocessing

A `ColumnTransformer` was used to apply **OneHotEncoder** to the categorical columns.

A `Pipeline` was then used to combine:

1. Preprocessing
2. XGBoost Classification

This makes the complete workflow cleaner and easier to manage.

## 🤖 Model Used

### XGBoost Classifier

The model was configured with:

* `n_estimators = 100`
* `max_depth = 5`
* `learning_rate = 0.1`
* `random_state = 42`

## 📈 Model Evaluation

The model was evaluated using:

### Accuracy

Measures the percentage of correct predictions.

### Classification Report

Provides:

* Precision
* Recall
* F1-score
* Support

### Confusion Matrix

Shows:

* True Positives
* True Negatives
* False Positives
* False Negatives

## 📊 Result

The XGBoost Classifier achieved an accuracy of:

**86.95%**

This indicates good predictive performance on the test dataset.

## 📝 Conclusion

An **XGBoost Classifier** was successfully implemented to predict bank customer churn.

The project demonstrated how categorical data can be handled using **OneHotEncoder**, how preprocessing and model training can be combined using a **Pipeline**, and how XGBoost can be used for classification problems.

The model achieved **86.95% accuracy** and was evaluated using Accuracy, Classification Report, and Confusion Matrix.

## 🚀 Key Learning

> XGBoost Classification can be used to build powerful predictive models for classification problems, while Scikit-learn Pipelines help combine preprocessing and model training into a single workflow.

---

### 👩‍💻 Author

**Sumaiya Nazneen**

Artificial Intelligence & Data Science
Python | Machine Learning | Data Science
