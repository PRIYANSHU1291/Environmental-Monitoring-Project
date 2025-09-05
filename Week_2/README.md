# Week 2 - Machine Learning Model Implementation

## Problem Statement
The goal is to build a predictive model for **Carbon Monoxide concentration (CO(GT))** using air quality sensor readings and environmental features (temperature, humidity, etc.). This will help analyze pollution levels and identify the best ML approach for air quality monitoring.

---

## Workflow

1. **Dataset Preparation**
   - Used the cleaned dataset from **Week 1** (9357 rows × 15 columns).
   - Features: PT08 sensor readings, NMHC, NOx, NO2, O3, T, RH, AH.
   - Target variable: **CO(GT)**.

2. **Data Splitting**
   - 80% training set and 20% testing set.

3. **Models Implemented**
   - **Linear Regression** (baseline model).
   - **Random Forest Regressor** (non-linear model for better performance).

4. **Evaluation Metrics**
   - R² Score → Goodness of fit.
   - RMSE (Root Mean Squared Error) → Average error magnitude.

---

## Results

- **Linear Regression**
  - R² Score: **0.51**
  - RMSE: **≈ 53.79**

- **Random Forest Regressor**
  - R² Score: **0.60**
  - RMSE: **≈ 48.41**

---

## Observations
- Linear Regression gave a decent baseline but struggled to capture complex relationships in the data.  
- Random Forest performed better with higher R² and lower RMSE, showing it can capture non-linear dependencies between pollutants and CO levels.  
- Feature importance from Random Forest suggests that **NOx, NMHC, and O3 sensors** play a key role in predicting CO concentrations.
