# Day 24: Decision Tree Bank Marketing Prediction 🌳

## 📌 Overview
This project uses a Decision Tree Classification algorithm to predict whether a customer will subscribe to a bank term deposit based on customer and marketing-related information.

## 🎯 Objective
- Understand the Decision Tree algorithm.
- Predict customer subscription behavior.
- Perform data preprocessing.
- Handle categorical and numerical features.
- Evaluate classification performance.

## 📂 Dataset
**Dataset:** `bank.csv`

**Target column:** `deposit` (or `y`, depending on the dataset).

Target labels:
- `yes` – Customer subscribed to a bank term deposit.
- `no` – Customer did not subscribe.

## ⚙️ Algorithm Used
**Decision Tree Classifier**

A Decision Tree is a supervised machine learning algorithm that makes predictions by learning decision rules from data.

### Model Configuration
- Criterion: Gini
- Maximum Depth: 5
- Random State: 42
- Class Weight: Balanced

## 🔄 Workflow
1. Import the required Python libraries.
2. Load and explore the bank marketing dataset.
3. Check missing values and duplicate records.
4. Analyze the target variable distribution.
5. Separate features and target.
6. Identify categorical and numerical columns.
7. Remove the `duration` feature to avoid data leakage in pre-call prediction.
8. Split the dataset into 80% training and 20% testing data.
9. Apply One-Hot Encoding to categorical features.
10. Train the Decision Tree Classifier using a Pipeline.
11. Make predictions on test data.
12. Evaluate the model using classification metrics.
13. Visualize the Decision Tree.
14. Save the trained model using Joblib.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

## 🌳 Decision Tree Visualization
The project visualizes the trained Decision Tree to understand how the model makes customer subscription predictions.

## 💾 Model Saving
The trained model is saved as:

`outputs/bank_marketing_decision_tree.pkl`

## 💡 Key Learnings
- Understanding Decision Tree Classification.
- Data preprocessing and feature selection.
- One-Hot Encoding.
- Handling imbalanced target classes.
- Preventing data leakage.
- Model evaluation and visualization.
- Saving trained machine learning models.

## ✅ Conclusion
This project demonstrates how Decision Tree Classification can be applied to bank marketing data to predict customer subscription behavior.



⭐ If you find this project useful, consider giving the repository a star!
