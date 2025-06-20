📈 Stock Price Prediction Project

The aim of the project is to investigate the performance of various machine learning models to predict stock market movements based on historical time series data and news article sentiment collected using APIs and web scraping. The basic principle would be to buy low and sell high, but the complexity arises in knowing when to buy and sell a stock.
A machine learning project to predict the stock prices of [e.g., META/Facebook] using historical data, technical indicators, and sentiment analysis.

Exploratory Data Analysis


The yfinance API will be used to download stock data for opening price (Open), highest and lowest price the stock traded at (High, Low), closing price (Close), number of stocks traded (Volume) and Adjusted Close. For the most part the Adjusted Close price will be selected for prediction purposes to take into account all corporate actions, such as stock splits and dividends, to give a more accurate reflection of the true value of the stock and present a coherent picture of returns.![download (1)](https://github.com/user-attachments/assets/31d11cff-7fe6-417e-95a3-ee3a447d56c7)

Time Series Analysis

![image](https://github.com/user-attachments/assets/21a9fbe2-fb0a-4cc5-945e-d1ca90ca18d5)


🛠️ Tech Stack

- Python (Pandas, NumPy, scikit-learn, yfinance)
- LSTM (Keras/TensorFlow or PyTorch)
- Jupyter Notebooks
- Matplotlib & Plotly
