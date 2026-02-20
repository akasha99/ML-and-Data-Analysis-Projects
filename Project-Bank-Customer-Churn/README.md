# Project: Customer Churn Analytics (Bank Customers)🏦📉

## 📌 Executive Summary
Customer retention is a critical metric for financial institutions. It is significantly more cost-effective to retain existing customers than to acquire new ones. This project develops a predictive analytics solution to identify high-risk customers likely to churn (exit the bank), enabling proactive retention strategies.

## 🎯 Project Objective
- **Goal:** Classify customers into "Stayed" or "Churned" categories based on demographic and financial behavior.
- **Problem Type:** Supervised Binary Classification.
- **Dataset:** Churn Modelling Dataset (Kaggle).

## 🛠️ Technical Workflow
1. **Data Engineering:** 
   - Pruned non-predictive identifiers (`RowNumber`, `CustomerId`, `Surname`).
   - Handled categorical variables using **Label Encoding** (Gender) and **One-Hot Encoding** (Geography).
2. **Feature Scaling:** Applied **StandardScaler** to normalize features like `Balance` and `EstimatedSalary` for optimal model convergence.
3. **Machine Learning:** Deployed a **Random Forest Classifier** to handle non-linear relationships and provide robust classification.
4. **Diagnostic Analysis:** Conducted **Feature Importance** analysis to pinpoint the primary drivers behind customer attrition.

## 📊 Key Insights & Results
- **Model Performance:** Achieved a classification accuracy of **~86%**.
- **Top Drivers of Churn:** 
  1. **Age:** Older customers showed a higher probability of exiting.
  2. **Number of Products:** Customers with fewer or extreme numbers of products were more likely to churn.
  3. **Geography:** Significant variance in churn rates observed across different regions (e.g., higher churn in Germany).
- **Evaluation Metrics:** Analyzed via Confusion Matrix and Classification Report (Precision, Recall, F1-Score).

## 💻 Tech Stack
- **Languages:** Python
- **Libraries:** Scikit-Learn, Pandas, NumPy, Seaborn, Matplotlib
- **Algorithms:** Random Forest Classification
