# Loan Approval Prediction

## 📌 Project Overview

This project focuses on predicting whether a loan application will be approved based on applicant details such as income, credit history, loan amount, and other financial indicators.

The goal is to build a machine learning model that assists banks and financial institutions in automating the loan approval process, reducing manual effort, and improving decision-making efficiency.

## 📂 Dataset

* **Source**: [Kaggle Loan Prediction Dataset](https://www.kaggle.com/datasets) *(replace with your dataset link if different)*
* **Size**: \~600 rows (train dataset) with features like:

  * `Gender`, `Married`, `Education`, `Self_Employed`
  * `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`
  * `Credit_History`, `Property_Area`
  * **Target**: `Loan_Status` (Y/N)

## ⚙️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas, NumPy** for data preprocessing
* **Matplotlib, Seaborn** for visualization
* **Scikit-learn** for machine learning models

## 🔑 Key Steps

1. **Data Preprocessing**

   * Handled missing values
   * Encoded categorical features
   * Applied normalization and feature scaling

2. **Exploratory Data Analysis (EDA)**

   * Visualized distributions and correlations
   * Identified key factors influencing loan approval

3. **Model Building**

   * Logistic Regression
   * Decision Tree
   * Random Forest
   * Support Vector Machine (SVM)

4. **Model Evaluation**

   * Accuracy, Precision, Recall, F1-score
   * Confusion Matrix

## 📊 Results

* Achieved **96% accuracy** using Random Forest (best model).
* Credit history and applicant income were the most important factors.

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/loan-approval-prediction.git
   cd loan-approval-prediction
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook LOAN_APPROVAL_PREDICTION.ipynb
   ```

## 📌 Future Work

* Deploy the model using Flask/Streamlit for real-time predictions.
* Hyperparameter tuning for better accuracy.
* Integrate with a web-based loan application system.
