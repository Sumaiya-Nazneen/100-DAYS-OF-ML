# 📊 Day 004 - Advertising Sales Prediction using Multiple Linear Regression

Welcome to **Day 004 of 100 DAYS OF ML 🚀**

This project implements **Multiple Linear Regression** to predict product sales based on advertising expenditure across different media channels.

---

## 📌 Project Overview

Multiple Linear Regression is a supervised Machine Learning algorithm used to predict a continuous target variable using multiple independent variables.

In this project:

- **Input Features (X):** TV, Radio, Newspaper
- **Target Variable (Y):** Sales

The model learns how advertising spending across different channels affects product sales.

---

## 🎯 Objective

The main objective is to predict **Sales** based on advertising expenditure on:

- 📺 TV
- 📻 Radio
- 📰 Newspaper

---

## 📂 Dataset

**Dataset:** `Advertising.csv`

The dataset contains advertising expenditure and corresponding sales data.

### Features

| Feature | Description |
|---|---|
| `TV` | Advertising expenditure on TV |
| `Radio` | Advertising expenditure on Radio |
| `Newspaper` | Advertising expenditure on Newspaper |
| `Sales` | Product sales - Target Variable |

---

## 🤖 Machine Learning Algorithm

### Multiple Linear Regression

Multiple Linear Regression models the relationship between one dependent variable and two or more independent variables.

The model uses:

**TV + Radio + Newspaper → Sales**

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore the data
4. Check data types and missing values
5. Analyze correlations
6. Visualize relationships
7. Define input and target variables
8. Split the dataset into training and testing sets
9. Train the Multiple Linear Regression model
10. Make predictions
11. Evaluate model performance

---

## 📊 Model Evaluation

The model can be evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📈 Key Learning

This project demonstrates how multiple advertising channels can be used together to predict sales.

It also provides practical experience with:

- Multiple Linear Regression
- Correlation Analysis
- Data Visualization
- Train-Test Split
- Model Training
- Prediction
- Model Evaluation

---

## 📁 Project Structure

```text
Day-004-Multiple-Linear-Regression-Advertising/
│
├── Advertising.csv
├── advertising.py
├── Multiple_Linear_Regression.ipynb
└── README.md
