# **Microsoft Stock Price Forecasting using ARIMA Model**

## **Project Overview**

This project involves building a Time Series Forecasting Model using the ARIMA (AutoRegressive Integrated Moving Average) method to predict the closing prices of Microsoft (MSFT) stock. The model aims to assist investors and analysts in predicting future stock prices based on historical data.

## **Research Question**

Can we accurately forecast Microsoft's stock closing prices using historical stock price data and time series analysis methods?

## **Dataset**

Source: Kaggle - Microsoft Stock Time Series Analysis

Data Used: Daily stock prices of Microsoft, including features such as Date, Open, Close, High, Low, and Volume.

## **Tools and Technologie*+s

* Python

* Pandas & NumPy: Data Manipulation

* Matplotlib & Seaborn: Data Visualization

* Statsmodels: Time Series Analysis

* Scikit-learn: Model Evaluation

* KaggleHub: Automated Dataset Downloading

## **Methodology**

Data Collection: Downloaded the dataset using KaggleHub.

## **Data Preprocessing:**

* Converted Date column to datetime format.

* Handled missing values through linear interpolation.

* Ensured business daily frequency for the stock price data.

* Visualization: Displayed the historical stock prices and performed seasonal decomposition to analyze trends and seasonality.

## **Model Building:**

Used ARIMA (5, 1, 2) model for time series forecasting.

Train-Test Split: 80% training data, 20% test data.

## **Model Evaluation:**

* Metrics used: MAE, MSE, and RMSE.

* Results: MAE = 19.46, MSE = 493.07, RMSE = 22.21.

* Key Findings

The model provided a reasonably good fit for forecasting stock prices.

The error metrics indicate an average prediction error of around $22.21 which is relatively moderate depending on the overall stock price level.

The visualization of Actual vs Predicted Prices showed that the ARIMA model generally follows the trend but could be improved for more precise forecasting.

## **Future Improvements**

* Hyperparameter Tuning: Explore different p, d, q values in the ARIMA model.

* Advanced Models: Implement models like Prophet by Meta or LSTM (Long Short-Term Memory) for better performance.

* Incorporate External Variables: Utilize additional market indicators or economic data to enhance model accuracy.
