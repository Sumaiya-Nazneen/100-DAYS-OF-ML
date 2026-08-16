# 🔤 Day 010 - Categorical Data Encoding

Welcome to **Day 010 of 100 DAYS OF ML CHALLENGE 🚀**

This project focuses on understanding and implementing **categorical data encoding** techniques in Machine Learning.

Machine Learning algorithms generally require numerical input, so categorical values such as colors, sizes, and materials need to be converted into numerical representations.

In this project, I practiced:

- Label Encoding
- One-Hot Encoding
- Train-Test Split
- Feature Transformation
- Linear Regression

---

## 📌 Project Overview

The project creates a sample product dataset containing categorical and numerical features.

The categorical features are:

- `color`
- `size`
- `material`

The numerical feature is:

- `price`

The goal is to convert categorical features into numerical representations so that they can be used by a Machine Learning model.

---

## 🎯 Objective

The main objectives of this project are:

- Understand categorical data
- Learn why encoding is required
- Implement Label Encoding
- Implement One-Hot Encoding
- Understand how categorical values are transformed
- Apply encoding separately to training and testing data
- Prepare encoded data for Machine Learning

---

## 📂 Dataset

The dataset is created using Python and NumPy.

A total of **1,000 rows** are generated.

### Dataset Features

| Feature | Type | Description |
|---|---|---|
| `color` | Categorical | Product color |
| `size` | Categorical | Product size |
| `material` | Categorical | Product material |
| `price` | Numerical | Product price |

The possible values are:

### Color

- Red
- Blue
- Green

### Size

- Small
- Medium
- Large

### Material

- Plastic
- Metal
- Wood

The price values are randomly generated between 100 and 499. :contentReference[oaicite:2]{index=2}

---

# 🔤 What is Categorical Data?

Categorical data represents values that belong to specific categories.

For example:

```text
Color:
Red
Blue
Green
