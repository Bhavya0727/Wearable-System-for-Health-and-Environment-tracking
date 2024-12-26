# Wearable-System-for-Health-and-Environment-tracking
## Overview
This project was developed in collaboration with the **ASSIST Lab at North Carolina State University** to analyze and visualize data collected from wearable health and environmental tracking systems. These systems monitor real-time metrics such as **ECG, heart rate, gyroscope, and environmental ozone exposure** to assist researchers in identifying patterns that predict exacerbated asthma conditions.

The project integrates **data cleaning**, **statistical analysis**, and **predictive modeling**, making it accessible and insightful for researchers.

---

## Objectives
- Build a **data pipeline** to process and clean sensor data for analysis.
- Use **SQL queries** in MS Access to assess signal quality and track device usage.
- Perform predictive analysis using machine learning models to evaluate heart rate abnormalities.

---

## Dataset
The dataset includes readings from wearable devices, recorded in **NumPy format**, covering:
- Health Metrics: ECG, gyroscope, heart rate.
- Environmental Metrics: Ozone exposure, device orientation, and motion.
- Device Usage: Duration and signal quality.

---

## Tools and Technologies
- **Database Management**: SQL, MS Access
- **Data Analysis**: Python (`NumPy`, `Pandas`), R
- **Machine Learning**: Regression analysis using `Neural Networks`, `Support Vector Regression`, and `Multiple Linear Regression`.

---

## Key Features

1. **Data Pipeline**:
   - Converted raw data from NumPy arrays to tabular format using Python.
   - Cleaned and standardized data using `Pandas` and grouped time-series readings for analysis.
   - Imported processed data into MS Access for storage and querying.

2. **Statistical Analysis**:
   - Assessed device signal quality and operational performance using SQL queries.
   - Conducted time-series analysis of health and environmental metrics.

3. **Predictive Analysis**:
   - Implemented machine learning models to predict heart rate abnormalities:
     - **Neural Networks**: Single-layer and double-layer models.
     - **Support Vector Regression**.
     - **Multiple Linear Regression**.
   - Evaluated models using regression metrics (`MSE`, `MAE`, `RMSE`) for performance comparison.

---

## Key Findings

1. **Device Usage**:
   - Identified usage patterns, including peak hours and days for device operation.

2. **Signal Quality**:
   - Cleaned and analyzed signal data, reducing inconsistencies by 15%.

3. **Predictive Modeling**:
   - Neural networks with double-layer architecture achieved the highest accuracy for predicting heart rate anomalies.
   - Regression analysis revealed significant relationships between health metrics (e.g., ECG) and heart rate.

---

## Visualizations
- **Health Metrics Trends**: Real-time trends for ECG, heart rate, and gyroscope data.
- **Device Usage Patterns**: Analysis of device usage by day and time.
- **Machine Learning Predictions**: Regression plots comparing predicted and actual heart rate values.

---
