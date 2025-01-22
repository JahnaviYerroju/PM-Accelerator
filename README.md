# PM-Accelerator

###Weather Trend Forecasting###

Dataset
The analysis uses the Global Weather Repository dataset. The dataset is available on Kaggle: Global Weather Repository


Methodology

Data Cleaning & Preprocessing:
Handled missing values using mean imputation
Removed outliers from temperature data using the IQR method
Normalized numeric data using MinMaxScaler


Exploratory Data Analysis (EDA):

Generated basic statistics using pandas' describe() function
Created visualizations for temperature distribution and precipitation vs. temperature relationship
Analyzed correlations between different weather parameters


Model Building:

Built an ARIMA model for temperature forecasting
Used the 'last_updated' feature for time series analysis
Evaluated model performance using MSE, MAE, and R-squared metrics


Results

Key findings from the analysis include:
Temperature distribution across different regions
Correlation between temperature and precipitation
Seasonal patterns in temperature data


Visualizations

Temperature Distribution
Precipitation vs Temperature
Forecast Results

