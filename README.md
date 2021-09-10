# ARIMA-LSTM-Stock-Price-Correlation-Coefficient-Prediction
When constructing and selecting a portfolio for investment, evaluation of its expected returns and risks is considered the bottom line. Minimizing risks and maximizing expected returns are objectives of Portfolio Optimization. In Modern Portfolio Theory correlation is used to include diversified assets that can help reduce a portfolio’s overall risk and hence optimize it. Stock price time series data encompasses both linear and non-linear tendencies. The ARIMA model being an ideal approach for tackling linear time series data and Recurrent Neural Networks being capable of understanding temporal dependencies and non-linearity well, we aim to develop a hybrid model (combining ARIMA and RNNs) for predicting the stock price correlation coefficient of two individual stocks.

## Problem Statement 
We aim to develop a hybrid model involving ARIMA and Neural Networks to predict future correlation coefficients of stock pairs, which would help in portfolio optimization. These stock pairs are randomly chosen from the S&P500 companies. In the first phase, the ARIMA model catches the linear tendencies in the time series data. Then, the LSTM model attempts to capture non-linearity in the residual values, which is the output of the former phase

## Dataset 
For the purpose of this paper, we consider the S&P500 firms adjusted closing price. The data is obtained using Yahoo! Finance API for a period of 01-01-2010 to 31-12-2019. The data has no missing values, and thus no pre-processing was needed at the forefront. Out of the 504 stocks on the S&P500 index list, we randomly chose 150 stocks. To make the process more robust in terms of randomness, we first chose 200 stocks randomly and then chose 150 stocks randomly from among them. The data set, which spans 2517 active days in total, is then used to calculate correlation coefficient values pairwise.

## Data Pre-Processing
- Checking for missing/null values
- Ajusting nominal Close Prices
- Calculating Correlation Coefficient 
- Spilitting into Train/Test and Validation Set

## Model Training
- Traditional Neural Network
- ARIMA Modeling 
- LSTM Modeling 

## Results




