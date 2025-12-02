# Airquality_timeseries_Prediction

This project focuses on forecasting the Air Quality Index (AQI) of Delhi by analyzing historical air-pollution data collected on an hourly basis. Since urban air quality fluctuates due to traffic, weather changes, and seasonal effects, accurate short-term prediction is essential for public health planning.

I built a multivariate time-series model that first predicts future pollutant concentrations and then calculates the AQI based on official Indian standards. Three forecasting approaches—ARIMA, Prophet, and LSTM—were implemented and compared. Among them, LSTM delivered the best accuracy, as it effectively captures temporal patterns, non-linear relationships, and long-term dependencies across pollutants.

The system also provides hourly forecasts, identifies the dominant pollutant, and generates the expected AQI for any future date, offering a transparent and data-driven tool for early air-quality alerts and decision-making.
