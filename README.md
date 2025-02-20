📈 Stock Price Prediction using LSTM in TensorFlow
📌 Overview
This project leverages Long Short-Term Memory (LSTM) neural networks to predict stock prices based on historical data. Using Yahoo Finance API, it fetches stock data, preprocesses it using MinMax scaling, and trains an LSTM model for forecasting future stock prices.
🚀 Features
• Fetches stock data for companies like Apple (AAPL) and Google (GOOGL).
• Uses TensorFlow/Keras LSTM model for time series prediction.
• Implements MinMax scaling for data normalization.
• Evaluates performance using Mean Squared Error (MSE).
• Visualizes stock price trends using Matplotlib.
🛠️ Requirements
Ensure you have the following dependencies installed:
pip install pandas numpy tensorflow scikit-learn matplotlib joblib
📂 Files
• Stocks_(1).ipynb → Jupyter Notebook containing the full stock price prediction pipeline.
🔧 How to Use
• Run the notebook to collect stock data from Yahoo Finance.
• Preprocess the data using scaling and feature engineering.
• Train the LSTM model using the historical data.
• Evaluate and visualize the predictions vs actual stock prices.
💡 Future Improvements
• Adding more stock symbols for broader analysis.
• Implementing Hyperparameter Tuning for improved accuracy.
• Exploring GRU or Transformer-based models for better forecasting.

