# 🏦 Loan Approval Prediction

This project predicts **loan approval status** based on applicant demographic, financial, and credit history information using **machine learning classification models**.  
I implemented and compared **Logistic Regression**, **Random Forest**, and **Decision Tree** classifiers, with results visualized using confusion matrices.  

The dataset used is the [Kaggle Loan Approval Prediction Dataset](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset) (provided in this repository).

---

## 📊 Features Used

The dataset contains a mix of **categorical** and **numerical** features, including:

- Number of dependents (`Dependents`)  
- Education level (`Education`)  
- Self-employed status (`Self_Employed`)  
- Aoplicant income (`ApplicantIncome`)  
- Loan amount (`LoanAmount`)  
- Loan term (`Loan_Amount_Term`)  
- Credit History (`Credit_History`)  
- marital status (`Married`)
- Coapplicant income (`CoapplicantIncome`)
- Property Area (`Property_Area`)
- Loan Status (`Loan_Status`)

---

## 🧪 Models & Methods

- **Logistic Regression** (`sklearn.linear_model.LogisticRegression`)
- **Random Forest Classifier** (`sklearn.ensemble.RandomForestClassifier`)
- **Decision Tree Classifier** (`sklearn.tree.DecisionTreeClassifier`)
- **Matplotlib** & **Seaborn** for visualization

---

## 📈 Results

- **Logistic Regression Accuracy:** `78.86%`
- **Random Forest Accuracy:** `77.24%`
- **Decision Tree Accuracy:** `69.11%%`

**Key Insight:**  
Logistic Regression and Random Forest had almost identical performance

---

## 📁 Dataset

- **Source:** [Kaggle Loan Approval Prediction Dataset](https://www.kaggle.com/code/redhorse22/loan-status-prediction/input)

---


## 📌 Requirements

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- seaborn  
- matplotlib  

---
