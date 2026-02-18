## Project 2: Medical Insurance Claim Prediction 🏥

### Objective
To build a regression model that estimates medical insurance charges based on personal and health attributes such as age, BMI, and smoking status.

### Approach & Optimization
1. **Baseline Model:** Started with **Linear Regression** to establish a benchmark.
2. **Feature Engineering:** Created an interaction feature `bmi_smoker` to capture the high-risk correlation between obesity and smoking.
3. **Advanced Modeling:** Implemented **Random Forest Regressor** to handle non-linear patterns in the data.

### Results
- **Initial MAE (Linear Regression):** ~$4,181
- **Final MAE (Random Forest):** ~$2,500
- **Improvement:** Successfully reduced prediction error by **~40%** through model optimization and feature engineering.

### Key Insights
- **Smoking** is the most significant factor affecting insurance costs.
- Non-linear models like Random Forest perform significantly better for healthcare cost estimation than simple linear models.
