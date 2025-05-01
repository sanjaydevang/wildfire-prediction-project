# wildfire-prediction-project

# 🔥 California Wildfire Prediction using Weather Data

This project uses historical weather and satellite fire detection data to model and predict wildfire risks across California from 2000 to 2025.

## 📌 Project Goals
- Analyze correlations between weather and fire occurrence
- Predict fire risk using:
  - XGBoost Regression
  - Logistic Regression
- Visualize key patterns and monthly trends
- Suggest recommendations for fire preparedness

## 📂 Dataset
- **CA_Weather_Fire_Dataset_1984_2025.csv**: Daily weather stats
- **ca_daily_fire_2000_2021.csv**: MODIS satellite fire data

## 🧠 Models
### 1. Logistic Regression
- Predicts **whether a fire will start** on a specific day
- AUC Score: **0.81**

### 2. XGBoost Regressor
- Predicts **number of fires observed**
- Features: MAX_TEMP, AVG_WIND_SPEED, PRECIPITATION

## 📊 Visuals
- Correlation Matrix
- Max Temp vs Fire Count
- Monthly Fire Trends

## ✅ Recommendations
- Trigger alerts when Temp > 80°F & Humidity < 30%
- Increase patrols in July–Sept
- Use model outputs for early warning

## 🛠️ Tools Used
- Python, Pandas, Seaborn, Matplotlib, XGBoost, Scikit-learn
- DuckDB for SQL-style queries
- Jupyter/Colab Notebooks

## 👥 Team
- Sanjay Devang – XGBoost Modeling & Visualization
- [Teammate 2] – Logistic Regression & ROC Analysis
- [Teammate 3–5] – Data Cleaning, Report Writing, EDA

## 📄 Report
See full summary in [report.pdf](./report.pdf)


