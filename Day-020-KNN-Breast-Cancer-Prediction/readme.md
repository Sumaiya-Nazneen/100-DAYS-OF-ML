# Day 20 – KNN | Breast Cancer Prediction 🎗️

## 📌 Overview

On Day 20 of my Machine Learning challenge, I implemented **K-Nearest Neighbors (KNN)** to classify breast tumors as **Malignant or Benign**.

The project uses the **Breast Cancer Wisconsin Dataset** and demonstrates the importance of **feature scaling** when using distance-based algorithms.

## 🎯 Objective

The objective is to predict whether a tumor is:

* `M` → Malignant
* `B` → Benign

For model training:

* `1` → Malignant
* `0` → Benign

## 📊 Dataset

**Dataset:** `Breast_Cancer.csv`

**Target Column:** `diagnosis`

The dataset contains numerical measurements describing characteristics of breast cell nuclei.

## 🧹 Data Cleaning

The following unnecessary columns were removed:

* `id`
* `Unnamed: 32`

The target column was separated from the input features.

## 🔢 Target Encoding

The categorical diagnosis values were converted into numerical values:

```text id="3bqz2b"
M → 1
B → 0
```

This allows the KNN algorithm to work with the target values.

## 🧠 Algorithm Used

### K-Nearest Neighbors (KNN)

KNN classifies a new data point based on the classes of its nearest neighboring data points.

For this project:

**K = 5**

The model looks at the **5 nearest neighbors** and uses them to determine the predicted class.

## 📏 Feature Scaling

KNN is a **distance-based algorithm**, so feature scaling is important.

`StandardScaler` was used to standardize the features before training the model.

```text id="j4qf4q"
Original Features
       ↓
StandardScaler
       ↓
Scaled Features
       ↓
KNN Classifier
```

## 🔄 Machine Learning Workflow

```text id="q5z9r2"
Load Dataset
     ↓
Check Missing Values
     ↓
Remove Unnecessary Columns
     ↓
Separate Features & Target
     ↓
Encode Target
     ↓
Train-Test Split
     ↓
Feature Scaling
     ↓
KNN Model
     ↓
Training
     ↓
Prediction
     ↓
Model Evaluation
```

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* StandardScaler
* KNeighborsClassifier

## 📈 Model Evaluation

The model was evaluated using:

### Accuracy

Measures the percentage of correct predictions.

### Confusion Matrix

Shows the correct and incorrect predictions for each class.

### Classification Report

Provides:

* Precision
* Recall
* F1-score
* Support

## 📊 Visualization

A **Confusion Matrix Heatmap** was created using Seaborn to visualize the model's classification results.

## 📝 Conclusion

The **KNN model** was successfully implemented to classify breast tumors as **Malignant or Benign**.

Feature scaling was performed using `StandardScaler` because KNN relies on distances between data points.

The model was evaluated using **Accuracy, Confusion Matrix, and Classification Report**.

## 🚀 Key Learning

> KNN is a simple distance-based classification algorithm, and proper feature scaling is essential when features have different ranges.

---

### 👩‍💻 Author

**Sumaiya Nazneen**

Artificial Intelligence & Data Science
Python | Machine Learning | Data Science
