# Student Performance Prediction — Machine Learning Pipeline

A machine learning project designed to predict students' exam scores based on study hours and attendance rates. Built using **Python**, **Pandas**, and **Scikit-Learn**.

---

## 📌 Project Overview
This project demonstrates an end-to-end Machine Learning workflow, including data preprocessing, feature engineering, model training using **Linear Regression**, and performance evaluation.

---

## 🧹 Data Preprocessing & Cleaning
- **Handling Duplicates:** Removed duplicate entries to prevent data bias.
- **Missing Values Imputation:** Filled missing values in `Study_Hours` and `Attendance_Rate` using column means.
- **Outliers Handling:** Handled unrealistic extreme values in study hours using median replacement.
- **Feature Scaling:** Applied `StandardScaler` to normalize feature ranges for the regression model.

---

## 📊 Model & Performance
- **Algorithm:** Linear Regression
- **Evaluation Metrics:**
  - **R² Score:** High variance coverage demonstrating strong feature correlation.
  - **RMSE:** Minimal root mean squared error indicating accurate predictions.

---

## 🛠️ Tech Stack
- Python
- Pandas & NumPy
- Scikit-Learn
- Matplotlib
-
