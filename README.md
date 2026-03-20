# Student Performance Analysis & Grade Prediction

## 📌 Project Overview

This project analyzes student academic behavior data to understand how study habits, attendance, and class participation influence academic performance. Machine learning models are applied to predict final student grades based on these behavioral factors.

The project is designed with an **academic and ethical approach**, following standards expected by **public German universities**.

---

## 🎯 Objective

* Analyze key factors affecting student performance
* Identify relationships between study habits and grades
* Build machine learning models to predict student grades
* Compare interpretable and ensemble models

---

## 📊 Dataset Description

* **Source:** Student Performance Dataset
* **Size:** 1,000,000 records
* **Features Used:**

  * Weekly self-study hours
  * Attendance percentage
  * Class participation score
* **Target Variable:** Final grade (A, B, C)

> Note: Identification variables and outcome-derived variables were removed to avoid data leakage and ensure academic integrity.

---

## 🧹 Data Preprocessing

* Removed irrelevant columns (`student_id`)
* Removed leakage-prone column (`total_score`)
* Verified absence of missing values
* Encoded categorical grade labels into numerical format

---

## 🔍 Exploratory Data Analysis (EDA)

Key observations from data visualization:

* Students with higher self-study hours tend to achieve better grades
* Attendance percentage shows a strong positive correlation with performance
* Active class participation significantly improves academic outcomes

EDA was performed using boxplots and statistical summaries.

---

## 🤖 Machine Learning Models

### 1️⃣ Logistic Regression

* Used as a baseline, interpretable classification model
* Suitable for academic and statistical analysis

### 2️⃣ Random Forest Classifier

* Ensemble model to capture non-linear relationships
* Improved predictive performance over baseline model

---

## 📈 Model Evaluation

* Metrics used:

  * Accuracy
  * Precision
  * Recall
  * F1-score

The Random Forest model achieved higher accuracy, while Logistic Regression provided strong interpretability.

---

## ⭐ Feature Importance

Feature importance analysis from Random Forest revealed:

1. Weekly self-study hours (most influential)
2. Attendance percentage
3. Class participation

These results align with exploratory data analysis findings.

---

## 🧠 Key Insights

* Regular self-study is the strongest predictor of academic success
* Attendance plays a crucial role in performance outcomes
* Classroom engagement positively impacts grades
* Behavioral data alone can effectively predict student performance

---

## 🛠 Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook
* GitHub

---

## 📌 Conclusion

This project demonstrates the application of data analytics and machine learning in the education domain. By combining exploratory analysis with predictive modeling, it highlights how behavioral factors can be leveraged to support academic monitoring and early intervention strategies.

---

