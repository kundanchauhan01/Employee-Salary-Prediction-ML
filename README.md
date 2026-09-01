# 💰 Employee Salary Prediction Using Machine Learning

A Machine Learning project that predicts an employee's estimated salary based on age, gender, education level, job title, and years of experience.

The project uses **Linear Regression** for salary prediction and a **Streamlit web application** for interactive predictions.

---

## 🚀 Live Demo

🔗 Coming soon...

---

## 📌 Project Overview

Salary prediction is a common regression problem where employee information is used to estimate their expected salary.

In this project, I built an end-to-end Machine Learning pipeline including:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Categorical Encoding
- Train/Test Split
- Linear Regression
- Model Evaluation
- Salary Prediction
- Model Deployment using Streamlit

---

## 📊 Dataset

The dataset contains employee information with the following features:

| Feature | Description |
|---|---|
| Age | Employee age |
| Gender | Employee gender |
| Education Level | Highest education qualification |
| Job Title | Employee's job role |
| Years of Experience | Total professional experience |
| Salary | Employee salary (Target) |

### Dataset Size

- Cleaned dataset used for modeling
- Target variable: `Salary`

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Handled missing values
- Removed duplicate records
- Standardized education categories
- Prepared numerical and categorical features
- Removed rows where the target salary was missing

---

## 📈 Exploratory Data Analysis

The project includes analysis of:

### Years of Experience vs Salary

Salary generally increases with years of professional experience.

### Age vs Salary

Age also shows a positive relationship with salary.

### Salary by Education Level

Salary distributions vary across different education levels.

---

## 🤖 Machine Learning Model

### Linear Regression

Linear Regression was selected as the primary regression algorithm for predicting salary.

### Features Used

```text
Age
Gender
Education Level
Job Title
Years of Experience
