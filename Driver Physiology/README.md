# Driver Physiological Dataset Analysis
## Overview
This project focuses on analyzing physiological signals collected from drivers to assess their emotional and cognitive states. The dataset includes continuous measurements such as heart rate, body temperature, and SpO₂ (oxygen saturation), along with labeled mood states. Monitoring driver physiology is essential for developing driver monitoring systems (DMS) that enhance road safety and reduce fatigue-related accidents.

The primary objective is to clean and preprocess the sensor data, explore physiological patterns, and build machine learning models to classify driver moods or stress levels based on biometric signals.

Dataset Source: Driver Physiological Dataset – Kaggle

## Dataset Description
The dataset is provided in XLSX format (to be converted to CSV) and contains the following fields:

Feature	Description
Time	Timestamp of the reading
Heart Rate	Beats per minute (BPM)
SpO2	Blood oxygen saturation level (%)
Body Temperature	Temperature in degrees Celsius
Mood	Driver’s mood, labeled as integers from 0 to 9

Note: The meaning of each mood label (0–9) is not explicitly defined, but can be mapped into classes like calm, stressed, distracted, etc., for classification.

## Project Goals
Convert and clean physiological data from Excel to CSV

Remove artifacts, null values, and outliers

Analyze temporal and physiological trends

Group mood labels into interpretable classes (e.g., Calm vs. Stressed)

Build classification models to predict driver mood based on biometric signals

## Analysis and Modeling Plan
📌 Exploratory Data Analysis (EDA)
Time-series plots of heart rate, temperature, SpO₂

Mood label distribution

Physiological signal variation per mood class

Correlation heatmaps

## Machine Learning Tasks
Binary classification (e.g., Calm vs. Stressed)

Multiclass classification (0–9 mood labels)

Models:

Logistic Regression

Random Forest

LSTM (for temporal sequence modeling)

## Tools & Technologies
Languages: Python

Libraries:

pandas, numpy, matplotlib, seaborn

scikit-learn, xgboost, tensorflow/pytorch (for DL)

openpyxl (for XLSX to CSV conversion)

## Data Cleaning Checklist
 Convert .xlsx to .csv

 Handle missing/null values

 Remove or smooth outliers (sensor errors)

 Normalize/standardize biometric signals

 Resample if needed for consistent time intervals

 Optional: Create new features (e.g., moving averages, deltas)

## Evaluation Metrics
Accuracy

Precision & Recall

F1-Score

Confusion Matrix

ROC-AUC (for binary mood detection)

## Acknowledgments
Dataset by Gowrishankar Achar, available on Kaggle

Special thanks to all researchers working to improve road safety and physiological signal analysis.

## Conclusion
This dataset provides a real-world opportunity to explore biometric signal processing, driver state classification, and human-centric AI applications. The ultimate goal is to contribute toward safer roads by predicting and preventing dangerous emotional or cognitive driver states using physiological signals.
