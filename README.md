Electricity Demand and Price Forecasting
This project focuses on developing accurate predictions for electricity demand and pricing using a multivariate time series forecasting approach. By integrating energy consumption and weather data from multiple cities in Spain, the project tackles challenges in the energy sector, leveraging advanced forecasting methodologies to enhance decision-making.
Objective
The aim is to predict electricity demand and pricing by utilizing a comprehensive dataset comprising energy and weather data. This project explores the relationship between weather metrics and energy consumption, identifying patterns and trends to enhance forecasting accuracy. The work also seeks to improve existing 24-hour forecasts provided by the Transmission System Operator (TSO) for electricity demand and pricing.
Objective
The aim is to predict electricity demand and pricing by utilizing a comprehensive dataset comprising energy and weather data. This project explores the relationship between weather metrics and energy consumption, identifying patterns and trends to enhance forecasting accuracy. The work also seeks to improve existing 24-hour forecasts provided by the Transmission System Operator (TSO) for electricity demand and pricing.
Methodology
The project follows a structured approach:

1. Data Integration and Exploration
Combine energy consumption, pricing, and weather data to create a multivariate dataset.
Use exploratory data analysis (EDA) to understand relationships and feature importance.
2. Preprocessing
Clean the data by handling null values and extracting features like hour, weekday, month, and year.
Check stationarity using the Dickey-Fuller test.
Normalize and reshape data for model training.
3. Model Development
Various forecasting models are implemented to predict electricity demand and pricing:

Machine Learning Models:
XGBoost Regressor
Deep Learning Models:
GRU, LSTM, CNN, CNN-LSTM, LSTM-Attention
Hybrid Models:
GRU-XGBoost, LSTM-Attention-XGBoost
4. Model Evaluation
Assess performance using Mean Absolute Error (MAE) for training and validation.
Compare model accuracy to identify the best-performing approaches.
Dataset Highlights
The dataset combines four years of data from:

Energy Metrics: Electricity consumption, pricing, and generation data from sources like fossil fuels, wind, and coal.
Weather Metrics: Temperature, humidity, pressure, wind speed, etc.
Data Sources:

Weather data: OpenWeather API
Energy data: ENTSOE Portal
Pricing data: Spanish TSO Red Electric España
Requirements
To execute the project, the following libraries are required:

General Libraries: pandas, numpy, matplotlib, seaborn, math
Machine Learning: XGBoost, scikit-learn
Deep Learning: TensorFlow, Keras
