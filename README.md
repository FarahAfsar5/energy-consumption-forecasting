# energy-consumption-forecasting

# ⚡ Energy Consumption Time Series Forecasting

## 📌 Project Overview
This project focuses on **forecasting short-term household energy usage** using the **Household Power Consumption Dataset**.  
We apply and compare **time series forecasting models** to understand energy demand patterns and improve prediction accuracy.  

### 🎯 Objective
- Parse and resample time series data
- Engineer time-based features (hour, weekday, weekend, etc.)
- Train and compare ARIMA, Prophet, and XGBoost models
- Evaluate performance using MAE and RMSE
- Visualize actual vs forecasted energy usage

---

## 📂 Dataset
- **Name:** Household Power Consumption Dataset  
- **Target Variable:** `Global_active_power` (in kilowatts)  
- **Resampling:** Hourly average  

---

## ⚙️ Methodology
1. **Data Preprocessing**
   - Parsing datetime
   - Handling missing values
   - Resampling to hourly averages
2. **Feature Engineering**
   - Hour of day
   - Day of week
   - Weekend/weekday
   - Month
3. **Modeling**
   - **ARIMA** for time series statistical modeling
   - **Prophet** for trend + seasonality
   - **XGBoost** for feature-based machine learning
4. **Evaluation**
   - **MAE (Mean Absolute Error)**
   - **RMSE (Root Mean Squared Error)**

---

## 📊 Results
| Model      | MAE    | RMSE   |
|------------|--------|--------|
| ARIMA      | ~X.XXX | ~X.XXX |
| Prophet    | ~X.XXX | ~X.XXX |
| XGBoost    | ~X.XXX | ~X.XXX |

*(Replace X.XXX with your actual results after running the notebook)*  

---

## 📈 Visualization
The notebook includes plots comparing:
- Actual household energy usage  
- Forecasted values from **ARIMA**, **Prophet**, and **XGBoost**  

---

## 🛠️ Skills Gained
- Time Series Forecasting  
- Feature Engineering  
- Model Comparison & Evaluation (MAE, RMSE)  
- Temporal Data Visualization  

---

## 🚀 How to Run
1. Open the provided Google Colab notebook.  
2. Upload the **Household Power Consumption dataset (CSV)**.  
3. Run all cells to train models and generate forecasts.  
4. View evaluation results and visualization plots.  

---

## 📌 Files in Repository
- `energy_forecasting.ipynb` → Google Colab notebook (code)  
- `household_power_consumption.csv` → Dataset  
- `README.md` → Project details & results  

---
