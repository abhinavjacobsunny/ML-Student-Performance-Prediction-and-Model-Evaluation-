# Student Performance Analysis & Machine Learning

## 📌 Overview

This project was completed as part of my **IDRA Internship**. The project analyzes student habits and academic performance using **Exploratory Data Analysis (EDA)** and **Machine Learning** techniques.

The analysis includes exam score prediction using Linear Regression and Pass/Fail classification using Logistic Regression.

## 🎯 Objectives

* Analyze student habits and academic performance.
* Perform Exploratory Data Analysis (EDA).
* Identify factors related to exam scores.
* Preprocess the dataset for Machine Learning.
* Predict exam scores using Linear Regression.
* Classify students as Pass or Fail using Logistic Regression.
* Evaluate the performance of the Machine Learning models.
* Identify meaningful insights from the dataset.

## 📊 Dataset

The dataset contains information about **1,000 students**, including:

* Age
* Gender
* Study hours per day
* Social media hours
* Netflix hours
* Part-time job
* Attendance percentage
* Sleep hours
* Diet quality
* Exercise frequency
* Parental education level
* Internet quality
* Mental health rating
* Extracurricular participation
* Exam score

## 🔍 Exploratory Data Analysis

The notebook performs:

* Dataset inspection
* Statistical analysis
* Missing-value analysis
* Numerical and categorical variable identification
* Distribution analysis
* Outlier detection
* Correlation analysis
* Feature relationships with exam scores
* Data visualization using Matplotlib and Seaborn

## 🤖 Machine Learning

### Linear Regression

**Target:** `exam_score`

Linear Regression is used to predict students' exam scores based on relevant academic, lifestyle, and behavioral factors.

Evaluation metrics include:

* MAE
* MSE
* RMSE
* R² Score

### Logistic Regression

The `exam_score` is converted into a Pass/Fail classification:

* **Pass:** Exam score ≥ 50
* **Fail:** Exam score < 50

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

Train and test performance are also compared to check for overfitting or underfitting.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* Jupyter Notebook

## ▶️ Project Workflow

1. The student performance dataset was uploaded to **Google Colab**.
2. The dataset was explored and analyzed using EDA.
3. Data preprocessing was performed.
4. Linear Regression was trained for exam score prediction.
5. Logistic Regression was trained for Pass/Fail classification.
6. Models were evaluated using appropriate performance metrics.
7. Key findings and insights were identified.
8. After completing and running the notebook, the **completed Jupyter Notebook was uploaded to GitHub**.

## 📁 Repository Contents

```text
Student-Performance-ML/
│
├── student_performance_ml_workflow.ipynb
├── Day18_19_student_habits_performance.csv
└── README.md
```

## 🎓 Internship

This project was **completed as part of my IDRA Internship**, providing practical experience in Data Analysis, Exploratory Data Analysis, Data Preprocessing, and Machine Learning.

## 👨‍💻 Author

**Abhinav Jacob Sunny**

B.Tech Student
