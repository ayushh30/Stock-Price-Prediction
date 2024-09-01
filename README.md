# Stock_Price_Prediction
## Stock Price Prediction using LSTM Neural Network
This repository contains the implementation and analysis of stock price prediction using LSTM neural networks for the top 6 S&P 500 companies. The project involves data sourcing, preprocessing, model development, and result analysis.
## Project Overview
Sourced a dataset of 6000+ records (from 2013 to 2018) on stock prices of Apple, Microsoft, Alphabet, Amazon, NVIDIA, and Meta Platforms.
Preprocessed data by filtering and scaling using pandas and MinMaxScaler, handling more than 30,000 data points.
Visualized stock prices and trading volumes for each company to understand the data distribution and trends.
## Model Development
Designed an LSTM Neural Network in Keras with 2 LSTM layers having 128 units each, followed by 2 Dense layers.
Extracted and prepared training and testing data sets, ensuring chronological splitting to maintain temporal relationships.
Achieved an average Root Mean Square Error (RMSE) of 3.975% across all companies, indicating effective predictive performance.
## Results Analysis
Analyzed prediction results using visual comparisons between predicted and actual stock prices.
Generated 6 plots (one for each company) demonstrating the effectiveness of the LSTM model in capturing stock price trends.
## Data Source
<a href = "https://www.kaggle.com/datasets/camnugent/sandp500"> S&P500 Stocks Data </a>
