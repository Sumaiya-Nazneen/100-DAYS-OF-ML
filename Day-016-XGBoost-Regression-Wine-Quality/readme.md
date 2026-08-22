# Day 16 – XGBoost Regression | Wine Quality Prediction 🍷

## 📌 Overview

On Day 16 of my Machine Learning challenge, I implemented **XGBoost Regression** to predict wine quality using the **Wine Quality Dataset**.

XGBoost Regressor is a powerful boosting algorithm that combines multiple decision trees to make accurate numerical predictions.

## 🎯 Objective

The objective of this project is to predict the **quality score of wine** based on its chemical properties.

## 📊 Dataset

**Dataset:** WineQT.csv

**Target Variable:** `quality`

The remaining columns are used as input features.

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* XGBoost

## 🔄 Workflow

```text
Load Dataset
     ↓
Understand Dataset
     ↓
Separate Features and Target
     ↓
Train-Test Split
     ↓
XGBoost Regressor
     ↓
Model Training
     ↓
Prediction
     ↓
Model Evaluation
```

## 🤖 Model Used

### XGBoost Regressor

The model was configured with:

* `n_estimators = 100`
* `max_depth = 5`
* `learning_rate = 0.1`
* `random_state = 42`

## 📈 Evaluation Metrics

The model was evaluated using:

### MAE – Mean Absolute Error

Measures the average absolute difference between actual and predicted values.

### MSE – Mean Squared Error

Measures the average squared difference between actual and predicted values.

### R² Score

Shows how well the model explains the variation in the target variable.

## 💡 Preprocessing

The input features in this dataset are numerical, so no categorical encoding was required.

The dataset was divided into:

* **80% Training Data**
* **20% Testing Data**

## 📝 Conclusion

An **XGBoost Regressor** was successfully implemented to predict wine quality scores.

The model was trained on the Wine Quality Dataset, predictions were generated on the test data, and performance was evaluated using **MAE, MSE, and R² Score**.

This project helped me understand how **XGBoost can be used for regression problems involving numerical target values**.

## 🚀 Key Learning

> XGBoost Regression can combine multiple decision trees sequentially to produce strong predictions for numerical values.
