# RCA-UNIT-1-ACTIVITY-AD3108-
MULTIPLE LINEAR REGRESSION 

# CIE 2 – Activity 1: Multiple Linear Regression

## Overview
This project implements Multiple Linear Regression to predict a continuous target using multiple numerical input features. It is completed as part of CIE 2 for the Regression and Classification Algorithms course.

## Objective
- Understand how multiple input features jointly explain a continuous target.
- Calculate regression coefficients manually using the normal equation.
- Verify manual calculations using Scikit-learn.
- Compare single-feature and multiple-feature models.
- Interpret coefficients, analyze residuals, check multicollinearity and evaluate model performance.

## Dataset
- **Dataset:** Diabetes Dataset
- **Source:** Scikit-learn
- **Dataset link:** https://scikit-learn.org/stable/datasets/toy_dataset.html#diabetes-dataset
- **Input features:** BMI, Blood Pressure, S5, S6
- **Target:** Disease progression (continuous numerical value)

## Methodology
1. Load and inspect the dataset.
2. Check data types, summary statistics, missing values and duplicates.
3. Visualize relationships using scatter plots and a correlation heatmap.
4. Perform manual regression calculation using five observations and two features.
5. Calculate the design matrix, XᵀX, Xᵀy and regression coefficients.
6. Verify the manual calculation using Scikit-learn.
7. Split the data into training and testing sets.
8. Train single-feature and multiple-feature Linear Regression models.
9. Evaluate using MAE, MSE, RMSE, R² and adjusted R².
10. Perform residual analysis and check multicollinearity using correlation and VIF.
11. Make a new prediction and write the conclusion.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## How to Run
1. Open the notebook using Google Colab or Jupyter Notebook.
2. Run all cells from top to bottom.
3. Review the generated graphs, tables and evaluation results.

## Results

- Single-feature model R²: ~0.233
- Multiple-feature model R²: ~0.454
- MAE: Single-feature ~52.26 and Multiple-feature ~44.30
- RMSE: Single-feature ~63.73 and Multiple-feature ~53.78
- Did multiple features improve performance? - Yes, adding multiple features significantly improved performance

## Conclusion
This activity demonstrates the implementation of Multiple Linear Regression using manual calculations and Python libraries. The performance of a single-feature model is compared with a multiple-feature model. Regression coefficients, residuals, multicollinearity and evaluation metrics are analyzed to understand model performance and limitations.

## GitHub Profile
https://github.com/complexiota
