# Ames Housing Price Prediction – Advanced Regression Techniques
This project explores advanced regression modeling techniques using a rich dataset of residential properties in Ames, Iowa. The goal is to build a robust model that predicts housing prices based on over 160 features capturing architectural details, property condition, neighborhood information, and more.

## Dataset Summary
Files included:

train.csv: Training dataset (with sale prices)

test.csv: Test dataset (no sale prices)

data_description.txt: Detailed data dictionary (163 features)

sample_submission.csv: Benchmark prediction format

Target: SalePrice — final sale price of the property in USD

Source: Kaggle - House Prices: Advanced Regression Techniques

## Project Objectives
 Clean and preprocess high-dimensional data (with missing values and categorical encoding)

 Conduct in-depth exploratory data analysis (EDA)

 Build and tune advanced regression models (including ensemble methods)

 Compare model performance using R², RMSE, MAE

 Analyze feature importance, multicollinearity, and overfitting

 Prepare a submission file suitable for Kaggle competition upload

 Deploy insights through visualizations or an interactive dashboard (optional)

## Tools & Technologies
Python

Pandas, NumPy – Data wrangling

Matplotlib, Seaborn, Plotly – Visualization

Scikit-learn, XGBoost, LightGBM, CatBoost – ML models

Statsmodels – Regression diagnostics

Optuna / GridSearchCV – Hyperparameter tuning

Jupyter Notebook – Analysis and prototyping

## Feature Engineering
Imputation strategies (mean, median, mode, group-wise, domain-informed)

One-hot encoding for nominal variables

Label encoding for ordinal features

Log transformation of skewed variables

Feature scaling (MinMax, StandardScaler)

Feature selection using:

Recursive Feature Elimination (RFE)

Lasso Regularization

Permutation importance

## Exploratory Data Analysis (EDA)
Key insights:

Neighborhood and OverallQual are highly correlated with SalePrice

Basement features, garage size, and year built show strong relationships

Features like PoolQC, MiscFeature, Alley have many missing values or rare occurrences

Log transformation of SalePrice improves model assumptions

## Regression Models Built
Model	Description
Linear Regression	Baseline with regular features
Ridge & Lasso	Regularized linear models
Random Forest	Ensemble tree-based model
XGBoost & LightGBM	Gradient boosting algorithms
Stacking Regressor	Meta-model combining all above

## Evaluation Metrics:
R² Score: Coefficient of determination

RMSE: Root Mean Squared Error

MAE: Mean Absolute Error

Cross-validation (CV) with KFold or StratifiedKFold


## Potential Enhancements
Feature interactions and polynomial features

SHAP / LIME for explainability

Deploy best model via Streamlit or Flask

Automate with MLflow or DVC

Integrate with Kaggle API for auto-submissions

## License
CC0: Public Domain
This dataset and project are intended for learning and demonstration purposes only.

## Acknowledgements
Data from: Kaggle - House Prices: Advanced Regression Techniques

Original dataset design by: Dean De Cock

Feature guide: data_description.txt


