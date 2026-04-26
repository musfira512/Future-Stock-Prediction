# Task 2: Stock Price Prediction

## Objective
Predict short-term stock prices using historical market data and machine learning models.

## Dataset Used
Historical stock data is fetched using the Yahoo Finance API via the `yfinance` library.  
Stock used: Apple Inc. (AAPL)

## Features Used
- Open  
- High  
- Low  
- Volume  
- Close (Target variable)

## Model Applied
- Linear Regression

## Workflow
- Data collection using yfinance API  
- Feature selection and preprocessing  
- Train-test split (time-series order maintained)  
- Model training using Linear Regression  
- Prediction of Close price  
- Visualization of actual vs predicted values  

## Key Results and Findings
- The model captures general trends in stock movement  
- Predictions follow the actual price pattern but are not exact  
- Performance is evaluated using regression metrics (R², MAE, RMSE) instead of accuracy  

## Conclusion
This task demonstrates basic stock price prediction using regression techniques. However, stock markets are highly complex, and more advanced models are required for higher accuracy.
