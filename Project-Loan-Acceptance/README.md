# Project: Personal Loan Acceptance Prediction

## 📌 Business Case
Direct marketing campaigns often suffer from low conversion rates and high costs. This project provides a data-driven solution for a financial institution to predict which customer segments are more likely to accept a personal loan offer (term deposit), allowing for highly targeted and cost-effective marketing.

## 🎯 Objective
- **Goal:** Build a classification engine to predict loan acceptance behavior.
- **Problem Type:** Supervised Binary Classification.
- **Dataset:** Bank Marketing Dataset (UCI Machine Learning Repository).

## 🛠️ Technical Workflow
1. **Exploratory Data Analysis (EDA):** Investigated the impact of job categories, age distribution, and marital status on conversion rates.
2. **Data Engineering:** 
   - Handled missing values and mapped target labels.
   - Applied **One-Hot Encoding** to categorical features.
3. **Machine Learning:** Trained a **Decision Tree Classifier**, chosen for its interpretability and ability to extract clear business rules.
4. **Strategic Analysis:** Conducted **Feature Importance** analysis to identify the top drivers of customer engagement.

## 📊 Strategic Insights
- **Key Predictors:** Analysis revealed that **Contact Duration** and **Previous Campaign Outcomes** are the strongest indicators of acceptance.
- **Target Segments:** High conversion potential was observed in specific job groups, particularly students and retirees.
- **ROI Recommendation:** The bank should prioritize leads with successful historical interactions, as they show a significantly higher propensity to convert.

## 💻 Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, Scikit-Learn, Seaborn, Matplotlib
- **Algorithm:** Decision Tree Classifier
