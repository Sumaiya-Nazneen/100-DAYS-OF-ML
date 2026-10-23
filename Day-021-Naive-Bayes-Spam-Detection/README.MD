# Day 21 – Naive Bayes Spam Detection 📩

## 📌 Overview

On Day 21 of my 100 Days of Machine Learning Challenge, I worked on **Spam Detection using Naive Bayes** to classify text messages as Spam or Ham (Not Spam).

This project demonstrates how Natural Language Processing (NLP) techniques and Naive Bayes can be used for text classification.

## 🎯 Objective

The objective is to classify SMS messages into two categories:

- **Spam:** Unwanted or suspicious messages
- **Ham:** Normal, legitimate messages

## 📊 Dataset

**Dataset:** SMS Spam Collection (`spam.csv`)

- `v1` – Message category
- `v2` – Message text

## 🧠 Algorithm Used

**Multinomial Naive Bayes**

Multinomial Naive Bayes is a probabilistic Machine Learning algorithm commonly used for text classification. It predicts a message category based on the words present in the message.

## 🔤 TF-IDF Vectorization

TF-IDF (Term Frequency–Inverse Document Frequency) converts text messages into numerical features that a Machine Learning model can process.

## 🔄 Workflow

1. Load the SMS dataset
2. Select message text and target labels
3. Split data into training and testing sets
4. Convert text into numerical features using TF-IDF
5. Train the Multinomial Naive Bayes model
6. Predict message categories
7. Evaluate model performance

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes
- Pipeline

## 📈 Evaluation Metrics

- **Accuracy:** Percentage of correctly classified messages
- **Precision:** How many messages predicted as spam were actually spam
- **Recall:** How many actual spam messages were correctly detected
- **F1 Score:** Balance between precision and recall
- **Confusion Matrix:** Summary of correct and incorrect predictions

## 📝 Conclusion

This project demonstrates how **Naive Bayes and TF-IDF** can be combined to classify SMS messages as Spam or Ham.

It helped me understand text preprocessing, feature extraction, probabilistic classification, and model evaluation.

## 🚀 Key Learning

Naive Bayes is a simple and efficient algorithm for text classification tasks such as spam detection.

---

### 👩‍💻 Author

**Sumaiya Nazneen**

Artificial Intelligence & Data Science  
Python | Machine Learning | Data Science
