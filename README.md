# Time-Series-Forecasting

## **Keywords**  
- Time Series Analysis  
- Data Visualization  
- ETS Models vs. Seasonal-ARIMA  
- Model Validation  
- Forecasting  

## **Introduction**  
This project focuses on **Time Series Forecasting** to predict **monthly sales** for a video game company. The goal is to assist in supply planning based on expected demand. The analysis was performed using **Python**, applying **time series models** such as **ETS (Error, Trend, Seasonal) and Seasonal-ARIMA**.  

## **Summary of Findings**  
The analysis begins with **preparing and visualizing the time series data**. The dataset was **validated**, ensuring it was suitable for time series modeling. The **last 4 periods** were held out for testing.  

Next, **Trend, Seasonality, and Error components** were examined using **decomposition plots**. Both **ARIMA and ETS models** were applied, and their **in-sample errors (RMSE, MAPE, and MASE)** were compared. The ETS model showed a **lower RMSE**, indicating a **narrower standard deviation**, while both models had MASE values below **1.00**, confirming accuracy.  

Finally, the **forecasting performance** of both models was evaluated using **holdout samples**, and the **best-fitting model** was selected to forecast the next **four periods**.
