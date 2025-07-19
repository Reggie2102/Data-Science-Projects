# Mumbai Real Estate Insights – Properties Dataset Analysis
Welcome to a data-driven deep dive into Mumbai’s dynamic real estate market. This project explores detailed records of over 12,600+ properties, including residential and commercial units, to uncover pricing trends, regional insights, and property characteristics.

## Dataset Summary
File: properties.csv

Records: 12,685 properties

Source Location: Mumbai, India

Collected Over: 10+ months

Format: Tabular

Size: 7.5 MB

## Project Objectives
* Clean and preprocess real-world property data (missing values, inconsistencies)

* Perform exploratory data analysis (EDA) to discover trends and anomalies

* Apply machine learning models for price prediction

* Extract geospatial insights on Mumbai’s real estate hot zones

* Create interactive dashboards (optional)

🏷* Engineer features like price per sq ft, amenity scores, or neighborhood profiles

* Key Features in Dataset
Feature Group	Examples
Property Info	Property Type, Bedrooms, Bathrooms, Area, Floor
Pricing	Price, Booking Amount, Maintenance, Price/sqft
Ownership	Freehold/Leasehold, Transaction Type
Furnishing	Furnished, Semi-Furnished, Unfurnished
Direction	Facing (East, West, North, etc.)
Amenities	Gym, Pool, Clubhouse, Lift, Parking, Security, etc.
Location	Area Name, Landmark, City (Mumbai)
Possession	Status, Possession Date
Utilities	Electricity & Water Status, Power Backup
Developer Info	Builder/Developer Name

Note: Amenities are encoded as binary (0 = Not Available, 1 = Available). NA indicates data not collected.

## Tools & Technologies
Python

Pandas, NumPy – Data preprocessing

Matplotlib, Seaborn, Plotly, Folium – Visualizations

Scikit-learn, XGBoost, LightGBM – Modeling

Jupyter Notebooks – Exploratory analysis

Streamlit / Dash (Optional) – Interactive dashboards

## Exploratory Data Analysis (EDA)
* Price distribution across Mumbai

* Area-wise average prices and amenities

* Type of properties and floor-level distribution

* Missing value heatmaps and imputation strategies

* Correlation analysis between features (e.g. carpet area vs. price)

* Machine Learning Goals
Predict Property Price based on:

Number of Bedrooms, Bathrooms

Furnishing Status

Area (sqft)

Location

Amenities

Developer

Property Type

ML Workflow:
Data Cleaning & Encoding

Feature Engineering

Train/Test Split

Model Training (Linear Regression, XGBoost, etc.)

Evaluation (RMSE, MAE, R²)

Feature Importance and SHAP Analysis


## License
CC BY-SA 4.0
Use freely with attribution. For educational, research, and non-commercial purposes.

## Acknowledgements
Dataset curated over 10+ months by independent collectors

Data sourced from multiple real estate platforms in Mumbai

Special thanks to contributors ensuring data accuracy and completeness

Let me know if you’d like help building a notebook for data profiling or a basic price prediction model based on this dataset.









