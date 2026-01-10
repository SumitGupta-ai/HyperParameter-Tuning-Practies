🌸 Iris Classification with Machine Learning

This project demonstrates a complete machine learning workflow on the classic Iris dataset, starting from a baseline model to advanced hyperparameter tuning using cross-validation.
---
## 📌 Project Overview

The goal of this project is to:

Understand baseline model performance

Compare different ML algorithms

Apply hyperparameter tuning

Observe the effect of tuning on model accuracy

---
## 🧠 Algorithms Used

Logistic Regression (Baseline Linear Model)

Random Forest Classifier

Default parameters

Tuned using GridSearchCV
---
## 📊 Dataset

Name: Iris Dataset

Type: Multiclass Classification

Classes: Setosa, Versicolor, Virginica

Features: Sepal length, Sepal width, Petal length, Petal width

---
## ⚙️ Workflow
1️⃣ Logistic Regression (Baseline Model)

Trained with default parameters

Used as a simple baseline

Accuracy evaluated on test data

---

2️⃣ Random Forest (Without Hyperparameter Tuning)

Trained using default RandomForest parameters

Compared performance with Logistic Regression

3️⃣ Hyperparameter Tuning (GridSearchCV)

Applied GridSearchCV with 5-fold cross-validation

Tuned the following parameters:

n_estimators

max_depth

max_features

criterion

Best parameters selected based on mean cross-validation accuracy

---
## 4️⃣ Final Model

Random Forest trained using the best hyperparameters

Evaluated on test data

Compared against baseline models

---
## 🏆 Results Summary

Model	Hyperparameter Tuning	Accuracy
Logistic Regression	❌	~1.00
Random Forest	❌	~1.00
Random Forest	✅	~1.00

Note:
The Iris dataset is simple and well-separated, so hyperparameter tuning does not significantly improve accuracy.
This behavior is expected and validates the correctness of the ML pipeline.

---
## 🧪 Key Learnings

Hyperparameter tuning follows the same process for all algorithms

Only the parameters change, not the logic

GridSearchCV selects the best parameters using cross-validation

Tuning does not always guarantee better accuracy

Proper comparison requires a baseline model

---
## 🛠️ Technologies Used

Python

NumPy

Pandas

Scikit-learn

Jupyter Notebook

---
## 🎯 Conclusion

This project demonstrates a clean and structured approach to:

Model comparison

Hyperparameter tuning

Industry-style ML experimentation

It serves as a strong foundation for applying the same workflow to real-world datasets.
