# Stock Price Predictor

**Description:**  
This project predicts the future stock prices of a company using historical data and an LSTM (Long Short-Term Memory) neural network. LSTM is a type of recurrent neural network (RNN) particularly effective for **time series prediction**.

**Features:**  
- Uses past 60 days of stock prices to predict the next day’s price  
- Visualizes actual vs predicted stock prices  
- Easy to change the stock ticker by replacing the CSV file  
- Optional: Can be upgraded into a Streamlit web app  

**Skills & Libraries Used:**  
- Python  
- Machine Learning (LSTM)  
- Data Preprocessing & Scaling  
- Data Visualization  
- Libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `tensorflow.keras`  

**Dataset:**  
- Historical stock prices in CSV format (example: `AAPL.csv`)  
- Columns: Date, Open, High, Low, Close, Volume  
- You can download stock CSVs from Yahoo Finance  

**How to Run:**  
1. Install required libraries:  
```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
