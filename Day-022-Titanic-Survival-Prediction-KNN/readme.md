# Day 22: Titanic Survival Prediction 🚢

## 📌 Overview
This project uses machine learning to predict whether a passenger survived the Titanic disaster based on passenger information such as age, sex, passenger class, fare, and family details.

## 🎯 Objective
- Understand a binary classification problem.
- Handle missing values in a dataset.
- Encode categorical features.
- Scale numerical features.
- Train and evaluate a machine learning model.

## 📂 Dataset
The project uses the `titanic.csv` dataset containing 1,309 passenger records.

**Target variable:** `survived`
- `0` – Did not survive
- `1` – Survived

## ⚙️ Algorithm Used
**Logistic Regression**

Logistic Regression is a supervised machine learning algorithm used to predict outcomes such as survival or non-survival.

## 🔄 Workflow
1. Load and explore the Titanic dataset using Pandas.
2. Remove the `name`, `ticket`, and `cabin` columns.
3. Separate features and the target variable.
4. Split the data into training and testing sets.
5. Handle missing numerical and categorical values.
6. Encode categorical features using One-Hot Encoding.
7. Scale numerical features using StandardScaler.
8. Train the Logistic Regression model.
9. Predict passenger survival.
10. Evaluate the model's performance.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Logistic Regression
- One-Hot Encoding
- StandardScaler

## 📊 Model Evaluation

| Metric | Score |
|---|---:|
| Accuracy | 77.48% |
| Precision | 81.72% |
| Recall | 64.41% |
| F1-score | 72.04% |

## 💡 Key Learnings
- Data preprocessing and missing-value handling.
- Categorical feature encoding.
- Feature scaling.
- Binary classification.
- Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix.

## ✅ Conclusion
This project demonstrates how Logistic Regression can predict Titanic passenger survival after data preprocessing and feature engineering.


⭐ If you find this project useful, consider giving the repository a star!
