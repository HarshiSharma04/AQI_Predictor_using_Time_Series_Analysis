# AQI Prediction and Time Series Analysis

## Project Overview
This project focuses on analyzing and predicting the Air Quality Index (AQI) using a dataset containing air quality measurements from various cities. The dataset includes features such as `PM2.5`, `PM10`, `NO2`, `SO2`, `CO`, and other pollutants, along with the corresponding AQI values. The goal of this project is to:
1. Perform **exploratory data analysis (EDA)** to understand trends and patterns in air quality.
2. Conduct **time series analysis** to study AQI trends over time.
3. Build **machine learning models** to predict AQI based on pollutant levels.

## Dataset
The dataset used in this project is `city_day.csv`, which contains daily air quality measurements for multiple cities. Key features include:
- **Date**: The date of the measurement.
- **City**: The city where the measurement was taken.
- **Pollutants**: `PM2.5`, `PM10`, `NO2`, `SO2`, `CO`, etc.
- **AQI**: The Air Quality Index, which is the target variable for prediction.

## Steps Performed
1. **Data Preprocessing**:
   - Handled missing values using forward and backward filling.
   - Encoded categorical variables (e.g., `City`) for machine learning.
   - Split the data into training and testing sets.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized AQI trends over time.
   - Analyzed the distribution of AQI across cities.
   - Studied correlations between pollutants and AQI.

3. **Time Series Analysis**:
   - Resampled data to observe monthly and yearly trends.
   - Decomposed the time series into trend, seasonality, and residuals.
   - Checked for stationarity using the Augmented Dickey-Fuller (ADF) test.
   - Plotted autocorrelation (ACF) and partial autocorrelation (PACF) to identify lags for ARIMA modeling.

4. **Machine Learning Models**:
   - Trained and evaluated models such as Linear Regression, Decision Trees, and Random Forests for AQI prediction.
   - Performed hyperparameter tuning to optimize model performance.

5. **Time Series Forecasting**:
   - Built an ARIMA model to forecast future AQI values.
   - Visualized the forecasted AQI trends.

## Key Insights
- **Trends**: AQI shows seasonal patterns, with higher pollution levels during certain months.
- **Correlations**: Pollutants like `PM2.5` and `PM10` have a strong positive correlation with AQI.
- **City-wise Analysis**: Some cities consistently have higher AQI values, indicating poorer air quality.
- **Forecasting**: The ARIMA model provides reliable forecasts for future AQI trends.

## Tools and Libraries Used
- **Python**: Primary programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning models.
- **Statsmodels**: Time series analysis and ARIMA modeling.

## How to Run the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/HarshiSharma04/AQI_Predictor_using_Time_Series_Analysis.git
