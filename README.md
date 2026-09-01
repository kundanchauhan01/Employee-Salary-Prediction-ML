# 💰 Employee Salary Prediction Using Machine Learning

A Machine Learning project that predicts an employee's estimated salary based on age, gender, education level, job title, and years of experience.

The project uses Linear Regression for salary prediction and a Streamlit web application for interactive predictions.

---

## 🚀 Live Demo

Coming Soon...

---

## 📌 Project Overview

This project predicts employee salary using Machine Learning.

The complete project workflow includes:

- Data Loading
- Data Cleaning
- Exploratory Data Analysis
- Feature Preparation
- Categorical Encoding
- Train/Test Split
- Linear Regression
- Model Evaluation
- Salary Prediction
- Streamlit Web Application

---

## 📊 Dataset

The dataset contains employee information used to predict salary.

### Features

- Age
- Gender
- Education Level
- Job Title
- Years of Experience

### Target

- Salary

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Handled missing values
- Removed duplicate records
- Standardized education categories
- Filled missing numerical values using the median
- Filled missing categorical values using the mode
- Removed rows where Salary was missing

---

## 📈 Exploratory Data Analysis

### Years of Experience vs Salary

The analysis shows a generally positive relationship between years of experience and salary.

### Age vs Salary

Age also shows a generally positive relationship with salary.

### Salary by Education Level

Salary distributions vary across different education levels.

---

## 🤖 Machine Learning Model

### Linear Regression

Linear Regression was used as the Machine Learning algorithm for predicting employee salary.

### Features Used

- Age
- Gender
- Education Level
- Job Title
- Years of Experience

### Target Variable

Salary

Categorical variables were converted into numerical features using One-Hot Encoding.

---

## 📊 Model Performance

The model was evaluated using MAE, RMSE, and R² Score.

| Metric | Result |
|---|---:|
| MAE | ₹14,860 |
| RMSE | ₹20,466 |
| R² Score | 0.8468 |

The model achieved an R² score of approximately 0.85, indicating that the model explains a substantial portion of the variation in salary within the test dataset.

---

## 🎯 Salary Prediction Example

Example employee:

- Age: 25
- Gender: Male
- Education Level: Bachelor's Degree
- Job Title: Data Analyst
- Years of Experience: 2

The trained Machine Learning model can estimate the employee's expected salary based on these inputs.

---

## 🌐 Streamlit Application

The trained Machine Learning model has been integrated into a Streamlit web application.

Users can enter:

- Age
- Gender
- Education Level
- Job Title
- Years of Experience

After clicking the Predict Salary button, the application displays the estimated annual salary.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Streamlit
- Jupyter Notebook

---

## 📂 Project Structure

```text
Employee-Salary-Prediction-ML/
│
├── app.py
├── Salary_Data.csv
├── Salary_Prediction_ML_Project.ipynb
├── salary_prediction_model.pkl
├── requirements.txt
└── README.md
