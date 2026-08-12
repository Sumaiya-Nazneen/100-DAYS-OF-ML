# 🍦 Day 006 - Polynomial Regression - Ice Cream Performance Prediction

Welcome to **Day 006 of 100 DAYS OF ML  🚀**

This project implements **Polynomial Regression** to model the relationship between temperature and ice cream sales.

---

## 📌 Project Overview

In this project, Polynomial Regression is used to capture a **non-linear relationship** between temperature and ice cream sales.

The model uses:

* **Input Feature:** `Temperature (°C)`
* **Target Variable:** `Ice Cream Sales (units)`

The dataset contains **49 records and 2 numerical columns**.

---

## 🎯 Objective

The objective is to build a Polynomial Regression model that predicts ice cream sales based on temperature and demonstrates how polynomial features can help a Linear Regression model learn non-linear patterns.

---

## 📂 Dataset

**Dataset:** `Ice cream selling data.csv`

### Features

| Feature                   | Description                          |
| ------------------------- | ------------------------------------ |
| `Temperature (°C)`        | Temperature value in degrees Celsius |
| `Ice Cream Sales (units)` | Number of ice cream units sold       |

The CSV contains the same two columns used in the notebook.

---

## 🤖 Machine Learning Algorithm

### Polynomial Regression

Polynomial Regression extends Linear Regression by transforming the original feature into higher-degree polynomial features.

In this project, a **degree of 3** is used:

```text
Polynomial Degree = 3
```

## The notebook uses `PolynomialFeatures(degree=3)` and then trains a `LinearRegression` model on the transformed data.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 🚀 Project Workflow

1. Import required libraries
2. Load the ice cream dataset
3. Explore the dataset
4. Calculate correlation
5. Visualize temperature vs. ice cream sales
6. Define input and target variables
7. Split the data into training and testing sets
8. Create polynomial features
9. Transform the training and testing data
10. Train the Linear Regression model
11. Generate predictions
12. Visualize actual vs. predicted values
13. Evaluate model performance

The notebook uses an **80% training and 20% testing split** with `random_state=0`.

---

## 📊 Correlation Analysis

The notebook calculates the correlation between temperature and ice cream sales.

The observed correlation is approximately **-0.175184** in the dataset.

---

## 📈 Model Evaluation

The project evaluates predictions using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

The notebook generates predictions using the trained polynomial regression model and compares them with the actual target values.

---

## 📚 Key Learnings

Through this project, I practiced:

* Polynomial Regression
* Polynomial Feature Transformation
* Non-linear Pattern Modeling
* Data Visualization
* Train-Test Split
* Model Training
* Prediction
* Model Evaluation
* Avoiding data leakage during transformation

The notebook specifically uses `fit_transform()` on training data and `transform()` on test data to apply the same learned polynomial mapping without fitting again on the test set.

---

## 📁 Project Structure

```text
Day-006-Polynomial-Regression-Ice-Cream-Performance-Prediction/
│
├── Ice cream selling data.csv
├── Polynomial_Regression_Ice_Cream.ipynb
└── README.md
```

---

## 🔮 Future Improvements

* Experiment with different polynomial degrees
* Compare Linear Regression and Polynomial Regression
* Perform cross-validation
* Tune the polynomial degree
* Compare model evaluation metrics
* Build a Streamlit prediction application



### 🚀 100 Days ML 

**Day 006 / 100 — Completed ✅**

⭐ Building Machine Learning projects every day.

### ✨ "Code. Learn. Build. Repeat."
