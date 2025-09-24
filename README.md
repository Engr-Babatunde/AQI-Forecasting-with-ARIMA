
## Air Quality Forecasting Project

This project focuses on forecasting Air Quality Index (AQI) values using time series analysis.
We applied the Autoregressive AR(1) model (AR(1)), which provided the best performance among tested models.

📊 Project Overview

Data Source: Historical AQI data (CSV file included).

Method: Autoregressive AR(1) time series model.

Forecasting Period: 30 days ahead.

Visualization: Forecast results plotted alongside historical AQI values.

⚙️ Workflow

Data Preparation

Loaded AQI dataset from CSV.

Checked for missing values and trends.

Model Selection

Tested multiple AR models.

Selected AR(1) as the most accurate model.

Forecasting

Generated 30-day AQI forecast.

Saved results into a CSV file for reference.

Visualization

Historical AQI plotted in blue.

Forecasted AQI plotted in red.

Confidence intervals shown with shaded area.

✅ Conclusion

The AR(1) model successfully captured the AQI trend.

Forecasting provides insights into air quality risk management.

Future improvements can explore seasonal ARIMA (SARIMA) or machine learning models for more complex patterns.
