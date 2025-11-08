* Stock Price Predictor

   This Python script predicts stock prices using Random Forest regression with PySpark.

* Features
   - Download historical stock data from Yahoo Finance
   - Generate features: price change, moving averages
   - Train Random Forest Regressor
   - Plot actual vs predicted prices
   - Predict next day's closing price

* Requirements
   - Python 3.10 or 3.11
   - PySpark
   - pandas
   - matplotlib
   - yfinance

* Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/rithikamalepati/Stock_Prediction_using_Pyspark.git
   cd Stock_Prediction_using_Pyspark

2. Install dependencies:
   pip install -r requirements.txt

3. Run the script:
  python stock_predictor.py

4. Enter the stock symbol (e.g., AAPL, TSLA) when prompted. A plot will appear, and tomorrow’s predicted closing price will be printed.

