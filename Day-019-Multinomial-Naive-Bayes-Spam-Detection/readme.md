# Day 19 – Multinomial Naive Bayes | Spam Detection 📩

## 📌 Overview

On Day 19 of my Machine Learning challenge, I implemented **Multinomial Naive Bayes** to classify SMS messages as **Spam or Ham (Not Spam)**.

The project uses **TF-IDF Vectorization** to convert text messages into numerical features that can be processed by the Machine Learning model.

## 🎯 Objective

The objective of this project is to classify SMS messages into:

* `spam` → Unwanted or promotional message
* `ham` → Normal message

## 📊 Dataset

**Dataset:** `spam.csv`

### Features Used

* `v2` → SMS message
* `v1` → Target label

The message text is used as the input feature, while the message category is the target.

## 🧠 Algorithm Used

### Multinomial Naive Bayes

Multinomial Naive Bayes is a probabilistic classification algorithm commonly used for **text classification** problems.

It works particularly well with features representing word counts or weighted word frequencies.

## 🔤 TF-IDF Vectorization

**TF-IDF (Term Frequency–Inverse Document Frequency)** converts text into numerical values.

It gives higher importance to words that are useful for distinguishing between different messages.

```text
SMS Message
     ↓
TF-IDF Vectorization
     ↓
Numerical Features
     ↓
Multinomial Naive Bayes
     ↓
Spam / Ham Prediction
```

## 🔄 Machine Learning Workflow

```text
Load Dataset
     ↓
Select Message & Label
     ↓
Train-Test Split
     ↓
TF-IDF Vectorization
     ↓
Multinomial Naive Bayes
     ↓
Model Training
     ↓
Prediction
     ↓
Model Evaluation
```

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* TF-IDF
* Multinomial Naive Bayes
* Pipeline

## 🔗 Pipeline

A Scikit-learn `Pipeline` was used to combine:

1. `TfidfVectorizer`
2. `MultinomialNB`

This allows text preprocessing and model prediction to be performed together.

## 📈 Model Evaluation

The model was evaluated using:

### Accuracy

Measures the percentage of correctly classified messages.

### F1 Score

Balances precision and recall.

### Classification Report

Provides:

* Precision
* Recall
* F1-score
* Support

### Confusion Matrix

Shows the number of correctly and incorrectly classified messages.

The model was evaluated on both the **training and testing datasets** to compare its performance.

## 📌 Train-Test Split

The dataset was divided into:

* **80% Training Data**
* **20% Testing Data**

`random_state=42` was used to make the split reproducible.

## 📝 Conclusion

A **Multinomial Naive Bayes Classifier** was successfully implemented for SMS spam detection.

TF-IDF was used to transform text messages into numerical features, and a Pipeline was created to combine the vectorization and classification steps.

The model was evaluated using **Accuracy, F1 Score, Classification Report, and Confusion Matrix**.

## 🚀 Key Learning

> Multinomial Naive Bayes combined with TF-IDF is an effective approach for text classification tasks such as SMS spam detection.

---

### 👩‍💻 Author

**Sumaiya Nazneen**

Artificial Intelligence & Data Science
Python | Machine Learning | Data Science
