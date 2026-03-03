# Employee Attrition Analysis
# 🏢 Employee Attrition Analysis & Prediction

## 📌 Project Overview
This project analyzes employee attrition using the IBM HR Analytics dataset and builds machine learning models to predict whether an employee is likely to leave the company.

The goal is to help HR departments identify key factors influencing employee turnover and take preventive actions.

---

## 🎯 Problem Statement
Employee attrition can significantly impact organizational productivity and costs.  
This project aims to:

- Analyze patterns behind employee attrition
- Identify key influencing factors
- Build predictive models to forecast attrition

---

## 📊 Dataset Information
- Dataset: IBM HR Analytics Employee Attrition Dataset
- Records: 1470 employees
- Features: 35 variables
- Target Variable: `Attrition` (Yes/No)

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights discovered:

- Employees working overtime are more likely to leave.
- Lower monthly income is associated with higher attrition.
- Years at company influences employee retention.
- Certain job roles show higher attrition rates.

---

## 🤖 Machine Learning Models Used

### 1️⃣ Logistic Regression
- Used as baseline model

### 2️⃣ Random Forest Classifier
- Performed better than Logistic Regression
- Used for feature importance analysis

---

## 📈 Model Performance

- Logistic Regression Accuracy: ~85% (approx)
- Random Forest Accuracy: ~87–90% (approx)

Since the dataset is imbalanced, evaluation was done using:
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📊 Top Important Features
According to Random Forest:

- OverTime
- MonthlyIncome
- YearsAtCompany
- Age
- JobRole
- TotalWorkingYears

---

## 💾 Model Saving
The trained Random Forest model was saved as:

employee_attrition_model.pkl

---

## ▶️ How to Run This Project

1. Clone the repository:
   git clone https://github.com/Gowda487/employee-attrition-analysis.git

2. Install dependencies:
   pip install -r requirements.txt

3. Open Jupyter Notebook:
   jupyter notebook

4. Run all cells in:
   employee-attrition-analysis.ipynb

---

## 📌 Conclusion
The analysis shows that workload and compensation are strong drivers of employee attrition.

The trained model can assist HR teams in predicting attrition risk and improving employee retention strategies.

---

## 👨‍💻 Author
Bhuvan M
Final Year Degree Student
