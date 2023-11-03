# Municipality Bus Utilization with Time Series Forecasting
A Jupyter Notebook program to implement municipality bus utilization forecasting with TES, SARIMA and LGBM models.

## General Information
This is a time series forecasting program implemented on Jupyter Notebook with the given dataset that provides hourly bus usage measurements for 10 municipalities.

It is required to forecast the hourly bus usage of those 10 municipalities for the last 2 weeks using time series forecasting and compare the results with real bus usage data.

The dataset format consists of: timestamp, municipality_id, usage, total_capacity. The models used for this implementation are TES, SARIMA and LGBM. 

* **RMSE Score Comparison of the Models**
<img title="RMSE Score Comparison of the Models" src="https://github.com/firatkorkmaz/Time-Series-Forecasting-Bus-Utilization/blob/main/images/Compare_Models.png">

* **Forecast Bus Usage of Municipality-4**
<img title="Forecast Bus Usage of Municipality-4" src="https://github.com/firatkorkmaz/Time-Series-Forecasting-Bus-Utilization/blob/main/images/Forecast_Municip_4.png">

## Setup & Run
Firstly, install the required libraries:
```
pip install -r requirements.txt
```
Then, run Jupyter Notebook and open the given notebook file **Municipality_Bus_Utilization.ipynb** in your web browser:
```
jupyter notebook
```
