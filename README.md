# 💰 Employee Salary Prediction ML

> An end-to-end Machine Learning project that predicts employee salary based on demographic, educational, professional, and job-related features.

## 🚀 Live Demo

👉 https://kundan-salary-prediction.streamlit.app/

## 📌 Overview

This project focuses on predicting employee salaries using Machine Learning regression techniques.

The complete workflow was developed in Jupyter Notebook, and the trained model was integrated into an interactive Streamlit web application for real-time salary prediction.

### Input Features

- Age
- Gender
- Education Level
- Job Title
- Years of Experience

### Target Variable

- Salary

---

## 🧠 Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Preparation
     ↓
Categorical Encoding
     ↓
Train / Test Split
     ↓
Linear Regression
     ↓
Model Evaluation
     ↓
Model Serialization
     ↓
Streamlit Deployment
```

---

## 📊 Model Performance

The Linear Regression model was evaluated using standard regression metrics.

| Metric | Score |
|---|---:|
| MAE | ₹14,860 |
| RMSE | ₹20,466 |
| R² Score | 0.8468 |

The model achieved an R² score of **0.8468**, indicating that it explains a substantial portion of the salary variation in the test dataset.

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Handled missing values
- Removed duplicate records
- Standardized categorical values
- Prepared numerical features
- Encoded categorical variables using One-Hot Encoding
- Separated features and target variable
- Split the dataset into training and testing sets

---

## 🤖 Machine Learning Model

### Linear Regression

Linear Regression was used as the primary Machine Learning algorithm to predict employee salary.

### Features Used

- Age
- Gender
- Education Level
- Job Title
- Years of Experience

### Target

- Salary

The trained model was saved using **Joblib** and integrated into the Streamlit application.

---

## 🌐 Streamlit Web Application

The trained Machine Learning model was integrated into an interactive Streamlit web application.

### Application Features

- Clean and interactive user interface
- Employee information input
- Real-time salary prediction
- Estimated annual salary output
- Model performance information

### 🚀 Live Application

https://kundan-salary-prediction.streamlit.app/

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Data Visualization |
| Scikit-learn | Machine Learning |
| Joblib | Model Serialization |
| Streamlit | Web Application |
| Jupyter Notebook | Model Development |

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
```

---

## ▶️ Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/kundanchauhan01/Employee-Salary-Prediction-ML.git
```

### 2. Open the Project Folder

```bash
cd Employee-Salary-Prediction-ML
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit Application

```bash
streamlit run app.py
```

The application will open in your default web browser.

---

## 🎯 Example Prediction

Example employee details:

| Feature | Value |
|---|---|
| Age | 25 |
| Gender | Male |
| Education Level | Bachelor's Degree |
| Job Title | Data Analyst |
| Years of Experience | 2 |

The trained Machine Learning model uses these features to generate an estimated annual salary.

---

## 💡 Key Learning

Through this project, I practiced:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Categorical Encoding
- Regression Modelling
- Model Evaluation
- Model Serialization
- Streamlit Application Development
- Machine Learning Deployment

---

## 🔮 Future Improvements

- Experiment with advanced regression algorithms
- Hyperparameter tuning
- Feature importance analysis
- Improve prediction accuracy
- Add interactive salary analytics
- Add salary range prediction
- Improve model monitoring

---

## 👨‍💻 Author

**Kundan Chauhan**

Data Analytics & Machine Learning Enthusiast

### GitHub

https://github.com/kundanchauhan01

### Live Project

https://kundan-salary-prediction.streamlit.app/

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.
