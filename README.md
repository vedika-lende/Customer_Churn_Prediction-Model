# Customer_Churn_Prediction-Model
A machine learning project that predicts customer churn using customer behavior and account data, helping businesses identify at-risk customers and improve retention strategies.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges for businesses. This project predicts whether a customer is likely to leave a bank based on demographic, account, and service-related information using Machine Learning classification algorithms.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction.

---

## 🎯 Problem Statement

The bank aims to minimize customer attrition by identifying customers who are likely to discontinue their relationship with the bank. Using historical customer data, the goal is to develop a predictive analytics model that enables proactive engagement and personalized retention efforts.

---

## 📂 Dataset

**Dataset:** Churn Modelling Dataset

The dataset contains customer information such as:

- Customer ID
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited (Target Variable)

**Target Variable**

- 0 → Customer Will Stay
- 1 → Customer Will Exit

---

## 🚀 Features

- Data Cleaning
- Handling Missing Values
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Label Encoding & One-Hot Encoding
- Feature Scaling
- Machine Learning Model Training
- Model Evaluation
- Customer Churn Prediction

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Streamlit
- Pickle

---

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── Churn_Modelling.csv
├── Python_Implementation_for_churn.ipynb
├── README.md
├── app.py
├── random_forest_churn_model.pkl
└── scaler.pkl
```
---

## ⚙️ Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Engineering
6. Encode Categorical Variables
7. Feature Scaling
8. Train-Test Split
9. Train Machine Learning Models
10. Evaluate Performance
11. Save Best Model
12. Predict Customer Churn

---

## 🤖 Machine Learning Algorithms2222

The project uses the Random Forest Classifier to classify customers into two categories:

Customer Will Stay
Customer Will Exit

The trained model and scaler are loaded into the Streamlit application for real-time predictions.

---

## 📊 Evaluation Metrics

- Accuracy Score
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

Navigate to the project directory

```bash
cd customer-churn-prediction
```

Install dependencies
```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

## 📈 Exploratory Data Analysis

The project includes various visualizations, including:

- Customer Age Distribution
- Gender Distribution
- Geography Distribution
- Correlation Heatmap
- Churn Distribution
- Balance Analysis
- Active Member Analysis
- Credit Score Distribution


---

## 📊 Results

The trained machine learning model successfully predicts whether a customer is likely to churn based on customer attributes. Model performance is evaluated using multiple classification metrics to ensure reliable predictions.

---

## 🔮 Future Improvements

- Hyperparameter Tuning
- Model Explainability using SHAP
- Streamlit Web Application
- Flask/FastAPI Deployment
- Docker Containerization
- Cloud Deployment (AWS/Azure/GCP)
- Batch Prediction using CSV Upload

---

## 📚 Learning Outcomes

Through this project, you will learn:

- Data Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Classification Algorithms
- Model Evaluation
- Machine Learning Pipeline
- Model Deployment
- Git & GitHub Best Practices

---

