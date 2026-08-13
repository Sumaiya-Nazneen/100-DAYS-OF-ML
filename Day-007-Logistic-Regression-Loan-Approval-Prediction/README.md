# 🏦 Day 007 - Loan Approval Prediction using Logistic Regression

Welcome to **Day 007 of 100 DAYS OF ML CHALLENGE 🚀**

This project implements **Logistic Regression** to predict whether a loan application will be approved based on applicant and loan-related information.

---

## 📌 Project Overview

Loan approval is a binary classification problem where the model predicts whether a loan application will be:

- ✅ Approved
- ❌ Not Approved

In this project, Logistic Regression is used to learn patterns from applicant information and predict the loan approval outcome.

---

## 🎯 Objective

The objective of this project is to build a Machine Learning classification model that can predict loan approval based on factors such as:

- Age
- Salary
- Credit Score
- Loan Amount
- Loan Term
- Employment Status
- Residence Type
- Previous Default

---

## 📂 Dataset

**Dataset:** `loan_approval_dataset.csv`

### Features

| Feature | Description |
|---|---|
| `Age` | Applicant's age |
| `Salary` | Applicant's salary |
| `Credit_Score` | Applicant's credit score |
| `Loan_Amount` | Requested loan amount |
| `Loan_Term` | Loan repayment term |
| `Employment_Status` | Employment category |
| `Residence_Type` | Type of residence |
| `Previous_Default` | Previous loan default history |
| `Loan_Approved` | Target variable |

The notebook uses `Loan_Approved` as the target variable. :contentReference[oaicite:4]{index=4} :contentReference[oaicite:5]{index=5}

---

## 🤖 Machine Learning Algorithm

### Logistic Regression

Logistic Regression is a supervised Machine Learning algorithm used for classification problems.

In this project:

```text
Applicant & Loan Information
              ↓
      Logistic Regression
              ↓
      Loan Approved?
       Yes / No
