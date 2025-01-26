
# Machine Learning Model Development and Evaluation

## Overview

This project focuses on developing machine learning models for predicting household energy consumption (Global active power). The process involved multiple stages, including exploratory data analysis (EDA), preprocessing, model training, evaluation, and final model selection. Below is a comprehensive overview of the steps and results.

## Folder Structure

- **data**: Contains raw and processed datasets used for model training and testing.
- **models**: Stores the trained models saved using Joblib.
- **notebooks**: Contains scripts for data preprocessing, model development, and evaluation.
- **results**: Includes evaluation metrics, visualizations, and final model outputs.

## Process Overview

1. **Exploratory Data Analysis (EDA)**: Analyzed the dataset to understand key features and relationships with the target variable.
2. **Preprocessing**: Included data cleaning, feature engineering, and splitting the dataset into training and testing sets.
3. **Model Development**: Trained 9 different models, including:
   - Linear Regression
   - Ridge Regression
   - Lasso Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - LGBM Regressor
4. **Model Evaluation**: Evaluated models based on multiple metrics:
   - Train and Test R²
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)

## Model Selection

After evaluating all 9 models, the **RandomForestRegressor (n_estimators=150)** was selected as the final model. This decision was based on the following reasons:

1. **Highest Performance Metrics**:
   - The model achieved the highest **Train R² (0.942)** and **Test R² (0.894)**, indicating strong predictive power and generalization capabilities.
   - It also exhibited the lowest **Test MSE (0.017)** and **Test RMSE (0.132)**, suggesting high accuracy and minimal error in predictions.

2. **Consistency**:
   - The model's performance was consistent across both the training and testing datasets, showing minimal overfitting and excellent generalization to unseen data.

3. **Visual Analysis**:
   - Predicted vs Actual visualizations and residual plots confirmed that this model's predictions were closely aligned with the true values, indicating robust model performance.

This model was chosen as the most reliable and effective for deployment.

## Instructions

### Accessing Results

- Open the CSV files with any spreadsheet software or use a Python library like Pandas to load and analyze them programmatically.
- View the PNG files with any image viewer or include them in reports or presentations.

### Using the Final Model Results

- The final model results represent the best-performing model after evaluation and comparison.
- These files can be directly used for reporting or further analysis.

## Notes

- Ensure all files are properly backed up and version-controlled to prevent data loss.
- If adding new results or visualizations, maintain the existing naming conventions for consistency.

