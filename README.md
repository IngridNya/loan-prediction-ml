# 🏦 Loan Prediction Machine Learning Project

This project focuses on predicting the approval status of a loan based on applicant information using machine learning. It walks through the end-to-end ML pipeline including data analysis, preprocessing, model training, evaluation, and insights.

---

## 📌 Objective

To build a classification model that can predict whether a loan should be approved or not using key financial and demographic attributes.

---

## 🗂 Dataset Overview

The dataset contains historical loan application records with features such as:

- **Gender**
- **Marital Status**
- **Education**
- **Self_Employed**
- **ApplicantIncome**
- **CoapplicantIncome**
- **LoanAmount**
- **Loan_Amount_Term**
- **Credit_History**
- **Property_Area**
- **Loan_Status** *(Target variable: Y/N)*

---

## 🔍 Exploratory Data Analysis

The notebook includes data inspection and visualizations to uncover patterns and relationships:

- Distribution of loan approval status
- Approval rates by gender, marital status, credit history, etc.
- Handling of missing values and outliers
- Summary statistics and insights using pandas, seaborn, and matplotlib

---

## 🧹 Data Preprocessing

- Imputed missing values (mean/mode)
- Dropped uninformative columns like `Loan_ID` and `Dependents`
- Encoded categorical variables
- Prepared the dataset for model training

---

## 🤖 Model Building

Several machine learning models were trained and tested:

- Logistic Regression
- Random Forest
- XGBoost

Models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

The best-performing model was selected based on generalization performance.

---

## 🚧 Deployment (To be implemented)

Model deployment using Flask is a planned feature. Once complete, users will be able to enter loan application details and receive real-time predictions.

> ✅ Deployment will be added in a future version.

---

## 💡 Key Learnings

- Built a complete ML pipeline on structured data
- Gained insights from real-world financial data
- Learned how categorical variables and credit history impact loan decisions
- Applied different ML algorithms and evaluated their performance

---

## 📁 Project Structure


---

## ⚙️ Tools Used

- Python
- pandas, numpy
- seaborn, matplotlib
- scikit-learn
- XGBoost

---

## 📌 Future Improvements

- Build a Flask web app to deploy the model
- Add user interface for real-time loan approval prediction
- Improve model accuracy with advanced feature engineering

---

## 📬 Contact

For questions or feedback, feel free to reach out or open an issue.
**Ingrid Nyakerario**  
📎 [LinkedIn](https://www.linkedin.com/in/ingrid-ong-uti-43a93361/)

---

⭐ **Feel free to star this repo if you found it helpful!**
