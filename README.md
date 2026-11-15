# House Price Prediction | Machine Learning

A Supervised Machine Learning project that predicts residential house sale prices using Python, Decision Tree Regression, and Random Forest Regression.

## Project Overview

The objective of this project is to develop and evaluate machine learning regression models to predict house sale prices based on property-related features.

The project covers the complete machine learning workflow, including data exploration, preprocessing, feature engineering, model development, evaluation, and feature importance analysis.

**Project Details**
- Dataset Size: 1,418 records
- Input Features: 12
- Target Variable: `SalePrice`
- Problem Type: Supervised Learning — Regression

## Tech Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib |
| Machine Learning | Scikit-learn |
| Development Environment | Jupyter Notebook |

## Dataset Description

The dataset contains residential property information, including:

- Overall Quality
- Year Built
- Total Basement Area
- Living Area
- Full Bathrooms
- Garage Type
- Garage Cars
- Garage Area
- Electrical System
- Fence
- Miscellaneous Features

**Target Variable:** `SalePrice`

## Project Workflow

### 1. Data Loading and Exploration
- Loaded the dataset using Pandas.
- Examined dataset dimensions and data types.
- Identified missing values.

### 2. Data Preprocessing
- Separated numerical and categorical features.
- Handled missing numerical values using Median Imputation.
- Handled missing categorical values using Most Frequent Imputation.
- Applied One-Hot Encoding to categorical variables.

### 3. Model Development
- Split the dataset into 80% training and 20% validation data.
- Implemented Decision Tree Regressor.
- Implemented Random Forest Regressor.

### 4. Model Evaluation
- Evaluated models using Mean Absolute Error (MAE).
- Used R² Score to measure model performance.
- Compared both regression models.

### 5. Model Tuning and Visualization
- Explored different `max_leaf_nodes` values for Decision Tree.
- Visualized actual versus predicted house prices.
- Performed Feature Importance Analysis using Random Forest.

## Machine Learning Models

The following regression algorithms were implemented:

1. Decision Tree Regressor
2. Random Forest Regressor

## Model Performance

Both models were evaluated on the validation dataset.

| Model | MAE | R² Score |
|---|---:|---:|
| Decision Tree | $21,599.41 | 0.847 |
| Random Forest | $19,803.99 | 0.860 |

### Best Performing Model: Random Forest

Random Forest achieved better performance with:
- Lower Mean Absolute Error.
- Higher R² Score.
- Better predictive performance compared to Decision Tree.

## Feature Importance Analysis

Feature importance analysis was performed using the Random Forest model to identify the most influential factors in house price prediction.

**Key Findings:**
- Overall Quality (`OverallQual`) was the most important feature.
- Above-ground Living Area (`GrLivArea`) was the second most influential feature.
- Total Basement Area (`TotalBsmtSF`) also contributed
