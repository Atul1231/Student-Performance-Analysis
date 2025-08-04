# 🎓 Student Performance Analysis & ML Modeling

This project focuses on analyzing and predicting student performance using multiple machine learning techniques and deep exploratory data analysis (EDA). The dataset used is **"Students Performance in Exams"**, containing exam scores and demographic attributes of students.

---

## 📌 Objectives

- Perform exploratory data analysis (EDA) to understand trends in student performance.
- Preprocess the dataset with encoding and scaling techniques.
- Train and evaluate classification and regression models:
  - **K-Nearest Neighbors (KNN)**
  - **Naive Bayes**
  - **Logistic Regression**
  - **Linear Regression**
- Gain hands-on experience in feature engineering and model evaluation.

---

## 📊 Dataset

- Source: [Kaggle - Student Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- Features include:
  - Gender, race/ethnicity, parental education, lunch type, test preparation course
  - Math, reading, writing scores
- Target:
  - For classification: `passed` (derived from average score)
  - For regression: `average_score`

---

## 🧹 Data Preprocessing

- Converted categorical variables using **Label Encoding** and **One-Hot Encoding**
- Derived new features:
  - `average_score` = mean of math, reading, writing scores
  - `passed` = 1 if average_score ≥ 40 else 0
- Removed unused string columns after encoding

---

## 📈 Exploratory Data Analysis

Visualizations included:
- Gender-wise and ethnicity-wise performance comparison
- Distribution plots of scores
- Correlation heatmap
- Pairplots to explore relationships between features

---

## 🤖 Machine Learning Models

### 🔹 Logistic Regression
- Used to classify whether a student passed based on demographic and academic features.
- Evaluation Metrics: Accuracy, Classification Report

### 🔹 K-Nearest Neighbors (KNN)
- Classified students as passed or not using distance-based logic.
- Evaluated using accuracy and confusion matrix

### 🔹 Naive Bayes
- Classified using probabilistic methods (Gaussian NB).
- Suitable for independent feature assumptions.

### 🔹 Linear Regression
- Predicted a student's average exam score based on features.
- Evaluation: MAE, MSE, R² Score
- Actual vs Predicted Score scatter plot

---

## 🧪 Model Evaluation

Each model was evaluated using appropriate metrics:

| Model             | Task Type     | Metrics                         |
|------------------|---------------|----------------------------------|
| Logistic Regression | Classification | Accuracy, Classification Report |
| KNN              | Classification | Accuracy, Confusion Matrix       |
| Naive Bayes      | Classification | Accuracy, Classification Report |
| Linear Regression| Regression     | MAE, MSE, R² Score               |

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn (sklearn)**

---

## 📁 Folder Structure

```

📦Student\_Performance\_Project/
┣ 📜 student\_performance.ipynb
┣ 📄 README.md
┗ 📊 StudentsPerformance.csv

```

---

## ✅ Conclusion

This project demonstrates a complete data science pipeline — from data preprocessing to EDA and machine learning modeling. It helped reinforce concepts of classification, regression, model evaluation, and data visualization.

---


## 🙋‍♂️ Author

**Atul Singh**

---
