# House Price Prediction | Machine Learning

A supervised Machine Learning project focused on predicting house sale prices using Decision Tree and Random Forest Regression algorithms.

---

## Project Overview

This project aims to predict residential house sale prices based on various property-related features using Machine Learning regression techniques.

The project involves data exploration, preprocessing, feature transformation, model development, performance evaluation, and model comparison.

**Dataset Size:** 1,418 records  
**Number of Features:** 12 input features  
**Target Variable:** `SalePrice`

---

## Tech Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib |
| Machine Learning | Scikit-learn |
| Development Environment | Jupyter Notebook |

---

## Dataset Description

The dataset contains residential property information, including:

- Overall Quality
- Year Built
- Total Basement Area
- Electrical System
- Living Area
- Full Bathrooms
- Garage Type
- Garage Cars
- Garage Area
- Fence
- Miscellaneous Features

**Target Variable:** SalePrice

---

## Project Workflow

**1. Data Loading & Exploration**
- Loaded the dataset using Pandas.
- Examined dataset dimensions, data types, and missing values.

**2. Data Preprocessing**
- Separated numerical and categorical features.
- Handled missing numerical values using Median Imputation.
- Handled missing categorical values using Most Frequent Imputation.
- Applied One-Hot Encoding to categorical variables.

**3. Model Development**
- Split the dataset into 80% training and 20% validation data.
- Implemented Decision Tree Regressor.
- Implemented Random Forest Regressor.

**4. Model Evaluation**
- Evaluated models using Mean Absolute Error (MAE).
- Used R² Score to measure model performance.
- Compared both regression models.

**5. Model Tuning & Visualization**
- Explored different `max_leaf_nodes` values for Decision Tree.
- Visualized actual versus predicted house prices using a scatter plot.

---

## Machine Learning Models

Two supervised regression algorithms were implemented:

1. Decision Tree Regressor
2. Random Forest Regressor

---

## Model Performance

The models were evaluated on the validation dataset.

| Model | MAE | R² Score |
|---|---:|---:|
| Decision Tree | $21,599.41 | 0.847 |
| Random Forest | $19,803.99 | 0.860 |

### Best Performing Model: Random Forest

Random Forest achieved better results with:
- Lower Mean Absolute Error.
- Higher R² Score.
- Better predictive performance compared to Decision Tree.

---

## Repository Structure

```text
House-Price-Prediction/
│
├── House_Price_Prediction.ipynb
├── housing data.csv
└── README.md
```

---

## How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone https://github.com/divyanshi-singh-17/House-Price-Prediction.git
```

**Step 2:** Navigate to the project directory.

```bash
cd House-Price-Prediction
```

**Step 3:** Install the required libraries.

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

**Step 4:** Launch Jupyter Notebook.

```bash
jupyter notebook
```

**Step 5:** Open `House_Price_Prediction.ipynb` and run all cells.

---

## Key Learnings

- Data Cleaning and Preprocessing
- Handling Missing Values
- Feature Transformation
- Regression Algorithms
- Model Evaluation and Comparison
- Hyperparameter Exploration
- Data Visualization

---

## Conclusion

This project demonstrates the application of supervised Machine Learning techniques for house price prediction.

Among the two implemented models, Random Forest achieved better performance with an R² Score of 0.860 and an MAE of $19,803.99.

The project provided practical experience in building, evaluating, and comparing regression models using Python and Scikit-learn.

---

## Author

**Divyanshi Singh**

Aspiring AI/ML Engineer | Data Science Enthusiast

[GitHub](https://github.com/divyanshi-singh-17) | [LinkedIn](https://www.linkedin.com/in/divyanshi-singh17/)
