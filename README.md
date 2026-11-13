# Comparative Evaluation of OLS, Ridge, Lasso, Elastic Net, and PLS for Baseball Player Salary Prediction

A comparative machine learning and statistical modeling project evaluating linear regression techniques for predicting Major League Baseball (MLB) player salaries based on performance statistics.

## 📌 Project Overview
Predicting athlete salaries involves handling high-dimensional data with strong multicollinearity among career and seasonal performance metrics (e.g., hits, runs, home runs, RBIs). This project benchmarks five regression approaches to determine which model generalizes best and handles correlated features most effectively:

1. **Ordinary Least Squares (OLS):** Baseline linear regression without regularization.
2. **Ridge Regression (\(L_2\)):** Penalizes large coefficients to handle multicollinearity.
3. **Lasso Regression (\(L_1\)):** Performs feature selection by shrinking less important coefficients to zero.
4. **Elastic Net:** Combines \(L_1\) and \(L_2\) penalties to balance feature selection and coefficient shrinkage.
5. **Partial Least Squares (PLS):** Projects predictors into a lower-dimensional space of orthogonal components.

## 📂 Dataset
* **Source:** Hitters Dataset (ISLR / MLB player statistics) 
* **Target Variable:** Player Salary
* **Features:** Seasonal and career batting/fielding statistics, league, division, and years in the major leagues.
