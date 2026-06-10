<p align="center">
  <img src="https://i.pinimg.com/originals/25/05/16/25051662be929d78194985190aeee50a.gif" width="600" height="400" alt="Bike Sharing GIF">
</p>

# 🚲 Bike Sharing Demand Prediction

## 📌 Project Overview

Bike-sharing systems have become an important component of modern urban transportation. Predicting bike rental demand helps service providers ensure bike availability, reduce waiting times, and optimize operational efficiency.

This project leverages Machine Learning techniques to forecast hourly bike rental demand based on weather conditions, seasonal factors, and time-related features.

---

## 📊 Dataset Information

The dataset contains the following features:

| Feature | Description |
|----------|------------|
| Date | Date of observation |
| Rented Bike Count | Number of bikes rented per hour (Target Variable) |
| Hour | Hour of the day |
| Temperature | Temperature in °C |
| Humidity | Humidity percentage |
| Wind Speed | Wind speed in m/s |
| Visibility | Visibility in 10m |
| Dew Point Temperature | Dew point temperature in °C |
| Solar Radiation | Solar radiation in MJ/m² |
| Rainfall | Rainfall in mm |
| Snowfall | Snowfall in cm |
| Seasons | Winter, Spring, Summer, Autumn |
| Holiday | Holiday / Non-Holiday |
| Functioning Day | Functional / Non-Functional Day |

---

## 🛠 Data Preprocessing

The following preprocessing techniques were applied:

- ✔️ Duplicate value detection and removal
- ✔️ Missing value analysis
- ✔️ Outlier treatment using IQR
- ✔️ Feature Engineering from Date column
- ✔️ Label Encoding for categorical variables
- ✔️ Feature Scaling using MinMaxScaler
- ✔️ Multicollinearity analysis using VIF

---

## 📈 Exploratory Data Analysis

Key insights discovered during EDA:

- Peak bike demand occurs during commuting hours.
- Temperature positively influences bike rentals.
- Rainfall and snowfall reduce bike rental demand.
- Summer and Autumn seasons exhibit higher rental activity.
- Functional days significantly impact bike usage patterns.
- Weather conditions play a crucial role in rental demand prediction.

### Visualizations Used

- Bar Charts
- Line Charts
- Box Plots
- Correlation Heatmaps
- Distribution Plots

---

## 🤖 Machine Learning Models

The following regression models were trained and evaluated:

- Linear Regression
- Lasso Regression
- Ridge Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

---

## 📏 Model Evaluation Metrics

Performance was measured using:

- R² Score
- Root Mean Squared Error (RMSE)
- Mean Residual Error

---

## 🏆 Best Performing Model

### XGBoost Regressor

The XGBoost model achieved the best results:

- High R² Score (~0.90)
- Low RMSE
- Near-zero Mean Residual Error

This demonstrates excellent predictive performance and strong generalization capabilities.

---

## 🔑 Important Features

Feature importance analysis identified the following influential variables:

- Functioning Day
- Temperature
- Rainfall
- Hour
- Seasons
- Solar Radiation

These factors significantly contribute to predicting bike rental demand.

---

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Jupyter Notebook

---

## 📂 Project Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis
5. Data Preprocessing
6. Model Building
7. Hyperparameter Tuning
8. Model Evaluation
9. Feature Importance Analysis
10. Conclusion & Insights

---

## 🎯 Conclusion

This project successfully predicts hourly bike rental demand using Machine Learning techniques. Among all evaluated models, XGBoost demonstrated superior predictive performance with an R² score close to 0.90.

The developed model can assist bike-sharing operators in improving inventory planning, reducing shortages, and enhancing customer satisfaction through data-driven decision-making.

---

## 📌 Author

**Tanuj Sanwal**

MCA Graduate | Data Analyst | Machine Learning Enthusiast

GitHub: https://github.com/sanwaltanuj7
