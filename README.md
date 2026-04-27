# 🧠 Employee Attrition Prediction 

## 📌 Overview  
This project focuses on predicting employee attrition and identifying the key factors that influence whether an employee stays or leaves a company. The goal is to help organizations make data-driven decisions to improve retention and reduce turnover.

---

## 💡 Problem Statement  
Employee turnover is costly and impacts productivity. In this project, I analyzed HR data to answer:  
👉 *What factors drive employees to leave a company?*  

Using machine learning, I built models to predict attrition and uncover key drivers like salary, satisfaction, and workload.

---

## 📊 Dataset  
- Source: Kaggle HR Analytics Dataset  
- ~15,000 employee records  
- Features include:
  - Satisfaction level  
  - Salary  
  - Number of projects  
  - Monthly hours  
  - Promotions  
  - Work accidents  

---

## ⚙️ Approach  

### 1. Data Preprocessing  
- Handled both categorical and numerical variables  
- Applied Label Encoding and Standard Scaling  
- Used PCA for dimensionality reduction  

**Flow:**  
Data → Cleaning → Encoding → Scaling → Feature Reduction  

---

### 2. Exploratory Data Analysis  
Key insights from visualizations:
- Employees with low salary are more likely to leave  
- Promotions positively impact satisfaction and retention  
- Higher workload correlates with attrition  

---

### 3. Models Used  
- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  
- Neural Networks  

---

## 📈 Results  

| Model              | Accuracy |
|-------------------|----------|
| Neural Network    | ~96%     |
| Random Forest     | **~98% (Best)** |
| Logistic Regression | ~76%   |
| SVM               | ~76%     |

👉 Random Forest performed the best due to its robustness and high accuracy.

---

## 🔍 Key Takeaways  
- Salary, satisfaction, and workload are major drivers of attrition  
- Machine learning models can effectively predict employee churn  
- Insights can help companies:
  - Improve retention strategies  
  - Reduce hiring costs  
  - Enhance employee satisfaction  

---

## 🚀 Why This Project  
I built this project to:
- Apply an end-to-end machine learning workflow  
- Work with real-world HR/people analytics data  
- Derive business-impactful insights beyond just model performance  

---

## 🛠️ Tech Stack  
- Python (Pandas, NumPy, Scikit-learn, SciPy)  
- Data Visualization (Matplotlib, Seaborn)
- Model Evaluation: Accuracy Score, Confusion Matrix, ROC Curve  
- Machine Learning Models  
- PCA for dimensionality reduction  

---

## 📌 What This Project Demonstrates  
- Strong data preprocessing and EDA skills  
- Ability to build and compare multiple ML models  
- Translating data into actionable business insights  
- Working with structured datasets in a real-world context  

---
