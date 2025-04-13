# ✈️ Air Passenger Time Series Forecasting

This project focuses on forecasting the number of monthly air passengers using time series analysis techniques in Python. It uses the classic Air Passenger dataset, a popular dataset for time series modeling.

---

## 📌 Project Objective

The goal is to build a forecasting model to predict future air passenger traffic. This helps airline companies plan resources, optimize schedules, and improve operational efficiency.

---

## 🧰 Tools & Libraries Used

- Python (Jupyter Notebook)
- Pandas & NumPy
- Matplotlib & Seaborn
- Statsmodels
- ARIMA Model
- ADF (Augmented Dickey-Fuller) Test

---

## 🔍 Workflow

1. **Data Exploration**
   - Load and inspect the dataset
   - Visualize the time series
2. **Check Stationarity**
   - Perform ADF test
   - Apply differencing if needed
3. **Decompose Time Series**
   - Identify trend, seasonality, and residuals
4. **Build Forecasting Model**
   - Use ARIMA to fit the model
   - Evaluate and fine-tune parameters
5. **Forecast Future Passengers**
   - Predict upcoming values
   - Compare predicted vs actual (if available)

---

## 📊 Output Example

Plots include:
- Original Time Series
- Rolling Mean and Std Deviation
- Seasonal Decomposition
- Forecasted vs Actual Data

---

## ✅ Results

- The SARIMA and Prophet model was able to capture the trend and seasonality effectively.
- Root Mean Squared Error (RMSE): _Add your RMSE if available_  
- This can help forecast demand and make data-driven business decisions.

---

## 📁 Dataset

- Dataset used: **Air Passenger Data (Monthly totals of international airline passengers from 1949 to 1960)**
- Source: Available in `statsmodels` library or from Kaggle

---

## 📌 Future Improvements

- Try more advanced models like SARIMA or LSTM
- Deploy the model as a web app using Streamlit or Flask
- Connect with real-time airline data APIs

----

