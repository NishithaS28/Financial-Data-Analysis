# Stock Price Prediction Using LSTM

This project uses Python to analyze and predict stock prices based on historical data. It focuses on:
- Analyzing 10 years of stock data using the `yfinance` library.
- Building a deep learning model (LSTM) to predict future stock prices.
- Visualizing the actual vs predicted stock prices.

## Features
1. **Data Analysis**: Includes moving averages for better trend analysis.
2. **Deep Learning Prediction**: Predicts stock prices using LSTM.
3. **Visualizations**: Plots closing prices, moving averages, and prediction trends.

## Outputs
- `closing_price.png`: Plot of stock closing prices over 10 years.
- `moving_averages.png`: Trend visualization of moving averages (20-day, 50-day).
- `lstm_predictions.png`: Plot showing actual vs predicted stock prices.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/Stock-Price-Prediction-Using-LSTM.git
   cd Stock-Price-Prediction-Using-LSTM
pip install -r requirements.txt

## Future Enhancements
- Use more technical indicators (e.g., RSI, MACD).
- Optimize the LSTM model for better accuracy.
- Extend predictions to real-time data.

## Results
The model achieved the following metrics:
- **Mean Squared Error (MSE)**: 162.69
- **Mean Absolute Error (MAE)**: 10.39
- **R² Score**: 0.943

These results demonstrate that the LSTM model effectively predicts stock prices with high accuracy.


## Run the Notebook
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YourUsername/YourRepoName/blob/main/Untitled5.ipynb)


### Key Takeaways
- The model is capable of forecasting future stock prices based on historical trends.
- Predicted prices closely align with actual values, making the model suitable for financial analysis.



**Disclaimer**: This project is for educational purposes only and should not be used for financial decision-making.
