Day 18 – Gaussian Naive Bayes | Diabetes Prediction 🩺

📌 Overview

On Day 18 of my Machine Learning challenge, I implemented Gaussian Naive Bayes (GaussianNB) to predict whether a person has diabetes using the Diabetes Dataset.

Gaussian Naive Bayes is a probabilistic classification algorithm that is commonly used for classification problems involving numerical features.

🎯 Objective

The objective of this project is to predict the "Outcome" of a patient:

- "0" → No Diabetes
- "1" → Diabetes

📊 Dataset

Dataset: "diabetes.csv"

Target Variable: "Outcome"

The dataset contains medical features such as:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

🧠 Algorithm Used

Gaussian Naive Bayes

Gaussian Naive Bayes assumes that the numerical features follow a Gaussian (normal) distribution.

It uses probability to determine which class a given observation is most likely to belong to.

🔄 Machine Learning Workflow

Load Dataset
     ↓
Separate Features & Target
     ↓
Check Missing Values
     ↓
Train-Test Split
     ↓
Gaussian Naive Bayes
     ↓
Model Training
     ↓
Prediction
     ↓
Model Evaluation

🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Gaussian Naive Bayes

📈 Evaluation Metrics

The model was evaluated using:

Accuracy

Measures the percentage of correct predictions.

F1 Score

Provides a balance between precision and recall.

Classification Report

Provides:

- Precision
- Recall
- F1-score
- Support

Confusion Matrix

Shows the correct and incorrect classification results.

📌 Train-Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

"random_state=42" was used to make the split reproducible.

📝 Conclusion

A Gaussian Naive Bayes Classifier was successfully implemented on the Diabetes Dataset to predict whether a patient has diabetes.

The model was trained using the numerical features, predictions were generated on the test data, and its performance was evaluated using Accuracy, F1 Score, Classification Report, and Confusion Matrix.

🚀 Key Learning

«Gaussian Naive Bayes is a simple and efficient probabilistic classification algorithm that can be applied to numerical datasets.»

---

👩‍💻 Author

Sumaiya Nazneen

Artificial Intelligence & Data Science
Python | Machine Learning | Data Science
