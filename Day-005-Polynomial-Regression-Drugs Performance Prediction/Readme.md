# 💊 Day 005 - Drugs Performance Prediction using Polynomial Regression

Welcome to **Day 005 of 100 DAYS OF ML CHALLENGE 🚀**

This project implements **Polynomial Regression** to model the relationship between age and drug performance.

---

## 📌 Project Overview

Polynomial Regression is a supervised Machine Learning algorithm used to model non-linear relationships between variables.

In this project:

- **Input Feature (X):** Age
- **Target Variable (Y):** Drugs_Perf

The model transforms the input feature into polynomial features and learns a non-linear relationship between age and drug performance.

---

## 🎯 Objective

The objective of this project is to understand Polynomial Regression and use it to predict drug performance based on age.

---

## 📂 Dataset

**Dataset:** `Drugs_Performance.csv`

### Features

| Feature | Description |
|---|---|
| `Age` | Input feature |
| `Drugs_Perf` | Target variable |

---

## 🤖 Machine Learning Algorithm

### Polynomial Regression

Polynomial Regression extends Linear Regression by adding polynomial terms such as:

```text
y = b₀ + b₁x + b₂x² + ... + bₙxⁿ
