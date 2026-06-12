# Student Performance Predictor

## Overview

This project uses Machine Learning to predict student exam scores based on various academic and lifestyle factors such as study hours, attendance, previous scores, assignment completion, and sleep duration.

The project follows a complete Machine Learning workflow including data analysis, visualization, model training, evaluation, and prediction.

---

## Problem Statement

Educational institutions often want to understand which factors influence student performance. This project aims to predict exam scores using student-related features and identify the most important factors affecting academic performance.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn

---

## Dataset Features

Input Features:

* Study_Hours
* Attendance
* Previous_Score
* Assignments_Completed
* Sleep_Hours

Target Variable:

* Exam_Score

---

## Project Workflow

1. Data Collection
2. Data Exploration
3. Data Cleaning
4. Correlation Analysis
5. Data Visualization
6. Feature Selection
7. Train-Test Split
8. Model Training using Linear Regression
9. Prediction
10. Feature Importance
11. Model Evaluation
12. Actual vs Predicted Plot

---

## Exploratory Data Analysis

The dataset was analyzed using correlation analysis and scatter plots to understand relationships between features and the target variable.

Key Findings:

* Previous_Score showed a strong positive relationship with Exam_Score.
* Study_Hours significantly influenced student performance.
* Attendance had a moderate positive impact on exam scores.

---

## Model Training

Linear Regression was used to train the prediction model.

The dataset was split into training and testing sets using:

* 80% Training Data
* 20% Testing Data

---

## Model Evaluation

The model was evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

These metrics help measure the prediction accuracy and overall model performance.

---

## Prediction Example

The trained model can predict exam scores based on student information such as:

* Study Hours
* Attendance
* Previous Score
* Assignments Completed
* Sleep Hours

---

## Future Improvements

* Use real-world educational datasets.
* Implement Decision Tree and Random Forest models.
* Perform Hyperparameter Tuning.
* Deploy the model using Streamlit.
* Build an interactive web application for predictions.

---

## Author

Gautam Giria

