# Traffic Forecast and Management System  

This project aims to forecast and manage traffic volumes using a dataset from Bengaluru. By leveraging advanced time-series analysis techniques and machine learning models, it provides accurate predictions to support effective traffic management.  

---

## Features  
- Utilizes Bengaluru traffic dataset for analysis and forecasting.  
- Generated additional features:  
  - **Previous Day Traffic Volume**  
  - **Daily Average Traffic Volume**  
  - **Peak or Off-Peak Indicator**  
- Normalized data using **Z-Score normalization** for better model performance.  
- Trained on 2 years of historical traffic data and tested on the last 45 days.  
- Visualized trends with:  
  - Seasonal Decompose Graphs  
  - ACF (Autocorrelation) and PACF (Partial Autocorrelation) plots.  
- Models Used:  
  - **ARIMA**  
  - **SARIMA**  
  - **LSTM**  

---

## Dataset
- Source: Bengaluru Traffic Dataset
- Time Range: 2 years for training and the last 45 days for testing.
- Preprocessing Steps:
Z-Score normalization
Feature engineering for daily averages and peak indicators.

## Models
- ARIMA (AutoRegressive Integrated Moving Average)
- SARIMA (Seasonal AutoRegressive Integrated Moving Average)
- LSTM (Long Short-Term Memory Neural Network)
