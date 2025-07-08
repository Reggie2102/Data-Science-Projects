# Heart Failure Clinical Data Analysis
## Overview
This project focuses on the analysis and predictive modeling of a heart failure dataset made available on Kaggle. Heart failure is a significant cause of morbidity and mortality worldwide. Early detection of patients at high risk of heart failure-related death is crucial in clinical settings.

This dataset contains clinical records of patients and is intended to support exploratory data analysis, machine learning classification tasks, and risk factor identification related to heart failure outcomes.

Dataset Source: Heart Failure Clinical Data on Kaggle

## Dataset Description
The dataset contains 299 patient records, each with 13 clinical features and 1 binary outcome indicating death due to heart failure.

Feature	Description
age	Age of the patient (years)
anaemia	Decrease of red blood cells or hemoglobin (boolean)
creatinine_phosphokinase	Level of the CPK enzyme in the blood (mcg/L)
diabetes	Whether the patient has diabetes (boolean)
ejection_fraction	Percentage of blood leaving the heart at each contraction (%)
high_blood_pressure	Whether the patient has hypertension (boolean)
platelets	Platelet count in the blood (kiloplatelets/mL)
serum_creatinine	Level of serum creatinine in the blood (mg/dL)
serum_sodium	Level of serum sodium in the blood (mEq/L)
sex	Gender of the patient (1 = male, 0 = female)
smoking	Whether the patient smokes (boolean)
time	Follow-up period (days)
DEATH_EVENT	Target variable: whether the patient died during the follow-up period (1 = yes, 0 = no)

## Project Objectives
Perform data cleaning and exploratory data analysis (EDA)

Identify key clinical predictors of mortality

Train and evaluate machine learning models for predicting the DEATH_EVENT outcome

Visualize patterns and correlations in the data to support clinical understanding

 Planned Analyses & Modeling
## Exploratory Data Analysis (EDA)
Class imbalance analysis

Distribution of clinical variables (e.g. age, ejection fraction)

Correlation heatmap between features and death events

Comparison of survivors vs. non-survivors

## Machine Learning Models
Logistic Regression

Random Forest


K-Nearest Neighbors (KNN)

## Evaluation Metrics
Accuracy

Precision & Recall

F1-Score

ROC-AUC Curve

## Technologies & Tools
Languages: Python

Libraries:

pandas, numpy, matplotlib, seaborn

scikit-learn, xgboost

imbalanced-learn (if resampling is needed)

## Acknowledgements
Dataset Source: Andrew Mvd on Kaggle

Dataset originally published in:
Davide Chicco and Giuseppe Jurman, “Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone,” BMC Medical Informatics and Decision Making (2020).

## License
Please refer to the Kaggle dataset page for licensing and usage terms.

## Conclusion
This dataset offers a valuable opportunity to practice building models in a real-world medical context. By analyzing and predicting heart failure death events, this project aims to bridge the gap between data science and life-saving healthcare applications.

