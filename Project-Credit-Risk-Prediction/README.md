# Project 1: Credit Risk Prediction 🏦

## Objective
The goal of this project is to automate the loan approval process by predicting whether an applicant is likely to default or not. This helps banks minimize financial risk.

## Dataset
- **Source:** Kaggle (Loan Prediction Dataset)
- **Features:** Applicant Income, Education, Credit History, Loan Amount, and Marital Status.

## Approach
1. **Data Cleaning:** Handled missing values using Mode (categorical) and Median (numerical).
2. **EDA:** Visualized the correlation between Credit History and Loan Status.
3. **Preprocessing:** Converted categorical text data into numerical values using One-Hot Encoding.
4. **Modeling:** Trained a **Logistic Regression** model.

## Results
- **Accuracy Score:** ~78.86%
- **Insights:** Credit History is the strongest predictor of loan approval.

## Tools Used
- Python (Pandas, Numpy, Seaborn, Matplotlib, Scikit-Learn)
