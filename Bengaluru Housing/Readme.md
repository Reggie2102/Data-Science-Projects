
# Dataset

- **Source**: [Kaggle - Bengaluru House Price Data](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)
- **Rows**: 13,000+
- **Columns**: Location, size, total_sqft, bath, balcony, price, area_type, availability

---

## Data Cleaning

- Converted non-uniform total_sqft ranges to numeric
- Removed extreme outliers (e.g., price per sqft anomalies)
- Reduced high-cardinality location by grouping rare ones
- Feature engineering:
  - price_per_sqft
  - bhk (from size)
  - Categorical encoding (location, area_type)

---

##  Exploratory Data Analysis

Key insights included:
- Price vs. Location distributions
- Relationship between sqft, bhk, and price
- Heatmaps for correlation
- Violin plots and boxplots of price ranges across area types

Example:

![Boxplot](assets/price_location_boxplot.png)

---

## Machine Learning Model

- **Model Used**: Linear Regression, Lasso, Random Forest
- **Final Model**: Random Forest (best RMSE)
- **Evaluation**:
  - R² Score: 0.82
  - RMSE: ~1.2 lakhs INR
- **Inputs**: Location, BHK, sqft, bath
- **Output**: Predicted price (in lakhs INR)

---

## Dashboard

Interactive Streamlit dashboard deployed to visualize:
- Average price per sqft by location
- Scatterplots of price vs. sqft
- BHK comparison filters
- Price prediction form
