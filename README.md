# Time-Series-Comparative-Analysis
JP Morgan Stock Price Analysis

## Introduction
Time series analysis can be useful to see how a given asset, security, or economic variable changes over time. Stock Market prices are something which change over time based on various factors such as Government Policies, Company News, Pandemics, Previous Prices etc

To study these trends, irregularities, and volatility in the stock prices, time series model(s) and techniques must be used. I chose data from one of the biggest financial firms in the world i.e. JP Morgan Chase and Co. to perform methods and forecasting using time series methods. This report includes the entire pipeline from data cleaning to fitting the model and forecasting the possible stock prices based on the historical data of stock currently available.

## Data Description
- The dataset contains the following columns:<br>
- Date (Daily)<br>
- Open Price of Stock on that day<br>
- High Price of Stock on that day<br>
- Low Price of Stock on that day<br>
- Close Price of Stock on that day<br>
- Adj Close of Stock<br>
- Volume of Stock<br>

The data changes based on previous values and other factors affecting companies' policies and follows some trends which can be captured using time series methods. Thus data used here is Discrete Time Series data.

## Objective
My objective here is to use multiple models on the dataset to perform analysis on the given dataset. The objective for my Time Series Data is:<br>
- Data Preprocessing and Analysis<br>
- Finding Trends in Data<br>
- Finding Correlations in Data<br>
- Finding if data is stationary or not<br>
- Checking Seasonality<br>
- Smoothening the data<br>
- Fitting all the models and validating their outputs<br>
- Which method is best for forecasting future values in data<br>

## Conclusion
After performing all the steps from preparing the data for implementation on the model to using various models like ARCH, GARCH, and CNN and using various error functions like MSE, MAE, RMSE, MAPE, and R2 I concluded using CNN for my dataset. The loss function used to compile my final model is MSE and the optimizer used is  ‘Adam’.
