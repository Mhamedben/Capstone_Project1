# Capstone Project: Predicting Diabetes Progression with Regression Analysis  

**Author:** Mhamed  
**Date:** 04, 22, 2025 


## Project Files:
* [Dataset: diabtes.csv] (https://github.com/Mhamedben/Capstone_Project1/blob/main/diabetes.csv)


* [Jupyter Notebook: predicting_diabtes_progression.ipynb] (https://github.com/Mhamedben/Capstone_Project1/blob/main/predicting_diabetes_progression.ipynb)

## Instructions on how to set up your virtual environment and run your notebook locally:

To run this notebook on your own computer: 
1. Clone the Repository:

git clone: https://github.com/Mhamedben/applied-ml-mhamed/blob/main/ML_RegressionMM/REGRESSION_PROJECT_Mhamed.ipynb.md

2. Create a Virtual Environment:
python -m venv .venv

3. Activate the Virtual Environment:
For windows: .\.venv\Scripts\activate
On macOS/Linux: .venv/bin/activate
 
## Introduction
Diabetes is a chronic medical condition that affects millions of people around the world and significantly impacts quality of life. According to the 2021 report of the International Diabetes Federation (IDF), approximately 537 million people worldwide were living with diabetes~\cite{website01}. Early prediction of disease progression is crucial for effective treatment planning and improved patient outcomes.
This project aims to develop a predictive model for diabetes progression using baseline clinical features such as age, sex, body mass index (BMI), blood pressure, and blood serum measurements. By applying regression analysis, the study seeks to identify key factors that influence disease progression and build a reliable model capable of forecasting future disease states.

## Section 1. Import and Inspect the Data
   - Load the dataset and display the first 10 rows.
   - Check for missing values and display summary statistics
    
## Section 2. Data Exploration and Preparation
   - Explore data patterns and distributions
   - Create histograms, boxplots, Scatter plots and count plots for categorical variables
   - Handle missing values and clean data
   - Correlation heatmap to explore feature relationships
     
## Section 3. Feature Selection and Justification
   - Choose Features and Target
   - Define X and y
   - Reflection 3: Why did you choose these features? How might they impact predictions or accuracy?

## Section 4. Feature Selection via Backward Elimination in OLS Regression
   - Split the data into training and test sets using train_test_split
   - Train model using Scikit-Learn model.fit() method.
   - Backward Elimination process
   - Summary of final model
   - Evaluate on Test Set

## Section 5. Check for Multicollinearity
   - Lasso (L1 Regularization) 
   - Ridge (L2 Regularization)
   - Compare performance of all models across the same performance metrics

