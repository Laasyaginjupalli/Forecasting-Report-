# Time Series Forecasting and Model Evaluation

## Project Overview

This project focuses on analysing monthly sales data covering January 2005 to February 2025 to forecast sales for the upcoming 12 months. Multiple time-series forecasting techniques were implemented and compared, including Simple Exponential Smoothing (SES), Holt-Winters, Prophet, Seasonal ARIMA (SARIMA), and Vector Autoregression (VAR). Model performance was evaluated using forecasting accuracy metrics such as RMSE and MASE, supported by visualisations and ACF/PACF analysis. The objective was to identify suitable forecasting approaches and demonstrate how predictive analytics can support business planning and data-driven decision-making.

## Objectives

- Analyse historical monthly sales data to identify trends and seasonal patterns.
- Apply multiple time-series forecasting techniques to predict future sales.
- Compare Simple Exponential Smoothing and Holt-Winters forecasting methods.
- Evaluate additive and multiplicative seasonality using Prophet.
- Examine residual patterns using ACF and PACF plots.
- Implement Seasonal ARIMA and evaluate its forecasting performance.
- Explore VAR modelling and Granger causality for multivariate time-series analysis.
- Compare model accuracy using RMSE and MASE.
- Identify suitable forecasting models to support business decisions.

## Methodologies & Frameworks

- Time-Series Analysis
- Simple Exponential Smoothing (SES)
- Holt-Winters Triple Exponential Smoothing
- Additive and Multiplicative Seasonality
- Prophet Forecasting
- Seasonal ARIMA (5,1,12)
- Vector Autoregression (VAR)
- Residual Analysis
- Autocorrelation Function (ACF)
- Partial Autocorrelation Function (PACF)
- Granger Causality Testing
- Model Evaluation (RMSE and MASE)

## Analytics Applications

- Monthly Sales Forecasting
- Trend and Seasonality Identification
- Forecast Accuracy Comparison
- Residual and Error Analysis
- Seasonal Demand Prediction
- Multivariate Time-Series Analysis
- Predictive Business Planning
- Data-Driven Decision Making

## Tools & Technologies

- Python
- Google Colab
- Prophet
- Time-Series Analysis Libraries
- Statistical Forecasting Models
- Data Visualisation

## Key Findings

- **Simple Exponential Smoothing:** Produced a flat forecast as it does not account for trend or seasonality, making it less suitable for the dataset.
- **Holt-Winters:** Captured underlying trends and recurring seasonal patterns more effectively than SES. However, its MASE score of 1.501 indicated that it performed worse than the seasonal naive benchmark.
- **Prophet:** The multiplicative seasonality model achieved a lower RMSE than the additive model, indicating a better fit for the increasing seasonal fluctuations in the dataset.
- **Trend Analysis:** The Prophet model identified an overall increasing trend with some periods of flattening and decline.
- **ACF and PACF:** Residual correlograms were used to examine remaining autocorrelation and assess whether the Prophet model had captured the underlying time-series patterns.
- **SARIMA:** Implemented a Seasonal ARIMA model with order (5,1,12) to explore an alternative statistical forecasting approach.
- **VAR:** Explored multivariate forecasting and Granger causality to understand how historical values of multiple time-series variables can contribute to future predictions.

## Key Skills

- Business Analytics
- Python Programming
- Time-Series Forecasting
- Predictive Analytics
- Statistical Modelling
- Prophet Forecasting
- Holt-Winters Modelling
- SARIMA
- Vector Autoregression (VAR)
- Additive and Multiplicative Seasonality
- Model Evaluation (RMSE, MASE)
- ACF and PACF Analysis
- Residual Diagnostics
- Granger Causality
- Data Visualisation
- Data-Driven Decision Making
