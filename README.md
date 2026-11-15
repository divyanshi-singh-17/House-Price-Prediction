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
- Total Basement Area (`TotalBsmtSF`) also contributed significantly to predictions.

This analysis helps understand the factors that influence the model's predictions.

## Repository Structure

```text
House-Price-Prediction/
│
├── House_Price_Prediction.ipynb
├── housing data.csv
├── requirements.txt
└── README.md
```

## Installation and Execution

### 1. Clone the Repository

```bash
git clone https://github.com/divyanshi-singh-17/House-Price-Prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd House-Price-Prediction
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Project

Open `House_Price_Prediction.ipynb` and execute all cells.

## Key Learnings

- Data Cleaning and Preprocessing
- Handling Missing Values
- Feature Transformation
- Regression Algorithms
- Model Evaluation and Comparison
- Hyperparameter Tuning
- Feature Importance Analysis
- Data Visualization

## Conclusion

This project demonstrates the practical application of supervised machine learning techniques for predicting residential house prices.

Among the implemented models, Random Forest achieved better performance with an R² Score of 0.860 and an MAE of $19,803.99.

The project strengthened practical understanding of data preprocessing, regression modelling, model evaluation, and feature importance analysis using Python and Scikit-learn.

## Author

**Divyanshi Singh**

Aspiring AI/ML Engineer | Data Science Enthusiast

[GitHub Profile](https://github.com/divyanshi-singh-17) | [LinkedIn Profile](https://www.linkedin.com/in/divyanshi-singh17/)
