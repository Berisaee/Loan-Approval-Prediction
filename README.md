# Loan Approval Prediction System

## Project Overview
The **Loan Approval Prediction System** is a Machine Learning project that predicts whether a loan application will be approved or rejected based on applicant details such as Income, Education, Employment Status, Loan Amount, Credit History, Marital Status, and other Financial Factors.

This project demonstrates the complete Machine Learning workflow including:
* Data preprocessing
* Handling missing values
* Data visualization
* Feature engineering
* Model training
* Model evaluation
* Accuracy comparison of multiple ML algorithms

The main goal of this project is to automate the loan approval prediction process using classification algorithms.

---

# Features
* Data cleaning and preprocessing
* Handling categorical and numerical data
* Missing value treatment
* Data normalization using MinMaxScaler
* Exploratory Data Analysis (EDA)
* Correlation Heatmap visualization
* Multiple Machine Learning models implementation
* Accuracy comparison of models
* Easy-to-understand workflow for beginners

---

# Technologies Used

## Programming Language
* Python

## Libraries & Frameworks
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# Dataset Information
The dataset contains applicant information used for predicting loan approval status.

## Important Features
* Gender
* Married
* Dependents
* Education
* Self_Employed
* ApplicantIncome
* CoapplicantIncome
* LoanAmount
* Loan_Amount_Term
* Credit_History
* Property_Area
* Loan_Status

### Target Variable
* **Loan_Status**
  
  * Y → Loan Approved
  * N → Loan Rejected

# Best Model Performance

| Model                        | Accuracy Score |
| ---------------------------- | -------------- |
| Logistic Regression          | **81.67%** ✅   |
| Random Forest Classifier     | 80.00%         |
| Support Vector Machine (SVM) | 70.83%         |
| Decision Tree Classifier     | 67.50%         |
| K-Nearest Neighbors (KNN)    | 64.17%         |

## Best Performing Model

The **Logistic Regression** model achieved the highest accuracy of **81.67%**, making it the best-performing model for loan approval prediction in this project.

---

# Machine Learning Workflow

## 1. Data Loading
The dataset is loaded using Pandas.

---

## 2. Data Preprocessing
### Handling Missing Values
* Numerical columns → Mean Imputation
* Categorical columns → Most Frequent Imputation

### Encoding Categorical Variables
Categorical data is converted into numerical format using Label Encoding.

### Feature Scaling
Numerical features are normalized using MinMaxScaler.

---

# Exploratory Data Analysis (EDA)
The project includes:
* Loan approval distribution visualization
* Correlation heatmap
* Categorical feature analysis
* Income and loan amount analysis

---

# Machine Learning Models Used
The following classification algorithms are implemented:
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

---

# Model Evaluation
Models are evaluated using:
* Accuracy Score
* Classification Report
* Confusion Matrix

The project also compares model accuracies visually using graphs.

---

# Results
* Successfully preprocesses loan applicant data
* Predicts loan approval status using ML algorithms
* Compares performance of multiple models
* Visualizes important insights from the dataset

---

# Future Improvements
* Deploy using Streamlit or Flask
* Add Hyperparameter Tuning
* Improve model accuracy
* Use advanced ensemble techniques
* Add real-time prediction interface

---

# Learning Outcomes
This project helps in understanding:
* Data preprocessing techniques
* Feature engineering
* Classification algorithms
* Model evaluation methods
* End-to-end Machine Learning pipeline

---

# Author
Sai Beri
