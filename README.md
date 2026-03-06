This Python script predicts future stock prices using Linear Regressor, Forrest Regressor or Gradient Boosting Regressor from historical stock data.
The script reads stock prices from an Excel file, trains a model for each stock, and visualizes(Only Gradient Boosting) both the historical data and predicted prices.

Features:
1. Read stock prices gathered from Data To Excel.py(StockInfo.xlsx)
2. Supports multiple stock columns in the dataset
3. Coverts dates into numeric values for modeling
4. Trains the models to predict future prices
5. Predicts stock prices days ahead
6. Visualizes historical data using Matplotlib

Libraries:
1. Pandas
2. numpy
3. matplotlib
4. scikit-learn

Note: I used VTuber companies but you can use all companies listed on Yahoo Finance
