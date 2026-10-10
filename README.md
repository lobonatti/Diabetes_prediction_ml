# Diabetes_prediction_ml
Diabetes prediction using R: comparing Logistic Regression, SVM, KNN, Classification Trees, Bagging and Random Forest.

# Diabetes Prediction Using Machine Learning in R

## Overview

This project applies and compares machine learning classification methods to predict diabetes using demographic and clinical data. The analysis focuses on identifying relevant predictors and evaluating model performance on an imbalanced dataset.

## Dataset

* **Source:** [Diabetes Prediction Dataset – Kaggle](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset/data)
* **Original dataset:** 100,000 observations and 9 variables.
* **Features:** Age, gender, hypertension, heart disease, smoking history, BMI, HbA1c level and blood glucose level.
* **Target:** Diabetes (binary classification).

A subset of 5,000 observations was selected after data cleaning and preprocessing.

## Methods

The project includes:

* Exploratory Data Analysis (EDA) and correlation analysis
* Data cleaning, preprocessing and standardization
* Logistic Regression
* Support Vector Machine (SVM) with hyperparameter tuning
* K-Nearest Neighbors (KNN) with cross-validation
* Classification Trees and pruning
* Bagging and Random Forest

Models are evaluated using accuracy, confusion matrices and class-specific classification performance.

## Key Results

The best reported accuracy among the evaluated models was **97.2%**, achieved by the pruned Classification Tree. However, the dataset is imbalanced, so accuracy alone does not fully capture the models' ability to identify diabetic patients.

## Tools

* R
* R Markdown
* Statistical Modeling
* Machine Learning
* Cross-Validation and Model Evaluation

## How to Run

1. Clone or download this repository.
2. Open the `.Rmd` file in RStudio.
3. Install the required R packages.
4. Update the dataset file path in the code to match your local environment.
5. Run the code chunks or knit the document to reproduce the analysis.

## Disclaimer

This project is for educational and analytical purposes only. The models are not intended for clinical diagnosis or medical decision-making.
