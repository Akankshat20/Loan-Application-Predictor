Hey there! I have made a Loan Application Predictor using Machine learning
# Loan Application Predictor

## Project Overview
This project aims to predict loan approval status using machine learning models. The approach includes hypothesis generation, exploratory data analysis (EDA), data preprocessing, model building, and evaluation.

## 1. Hypothesis Generation and Data Analysis
- **Objective**: To generate and test hypotheses related to loan approval and analyze data patterns.
- **Techniques Used**:
  - **Univariate Analysis**: Analyzed individual features with bar plots and box plots.
  - **Bivariate Analysis**: Examined relationships between features using heatmaps.

## 2. Data Preprocessing
- **Handling Missing Data**: Imputed missing values for categorical features using mode and for numerical features using the median.
- **Outlier Treatment**: Managed outliers and applied log transformation to correct skewness in the data.
- **Feature Engineering**:
  - Created dummy variables for categorical features to facilitate model training.

## 3. Model Building and Evaluation
- **Models Built**:
  - **Logistic Regression**: Used to predict loan approval status.
  - **Decision Tree**: Compared performance with logistic regression.
- **Model Evaluation**:
  - Achieved **87.8% accuracy** and **92.1% F1-Score**.
  - Utilized **stratified k-fold cross-validation** to ensure robust model validation.

