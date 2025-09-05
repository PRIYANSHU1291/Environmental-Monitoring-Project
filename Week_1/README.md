# Week 1 - Dataset Selection and Preprocessing

## Project Theme
Environmental Monitoring & Pollution Control

## Dataset
- **Name:** UCI Air Quality Dataset  
- **Source:** UCI Machine Learning Repository (also available via Kaggle/Zenodo)  
- **Description:** The dataset contains hourly responses from an array of gas multisensor devices deployed in an Italian city.  
  - Features include: CO(GT), NOx(GT), NO2(GT), O3 sensor values, Temperature (T), Relative Humidity (RH), Absolute Humidity (AH), etc.  
  - Shape after preprocessing: **9357 rows × 15 columns**  

## Problem Statement
The aim of this project is to analyze and predict air pollution levels, particularly Carbon Monoxide (CO) concentration, using environmental and sensor data.  
This can support air quality monitoring and pollution control strategies.

## Tasks Completed in Week 1
1. **Searched and selected dataset** related to the theme of pollution monitoring.  
2. **Loaded dataset in Python** using pandas with the correct delimiter (`;`) and decimal format (`,`).  
3. **Preprocessed the dataset** by:  
   - Removing unnecessary empty columns and rows  
   - Resetting the index for clarity  
4. **Explored dataset** using:
   - `.info()` to check structure and datatypes  
   - `.describe()` to get summary statistics  
   - `.isnull().sum()` to check for missing values  

## Improvisations Done
- Fixed incorrect CSV loading by specifying `sep=';'` and `decimal=','`.  
- Dropped empty rows/columns and reset index to clean the dataset.  
- Verified correct dataset shape and datatypes before further ML work.  

---
✅ With Week 1 completed, the dataset is now ready for feature selection, handling missing values, and model implementation in **Week 2**.
