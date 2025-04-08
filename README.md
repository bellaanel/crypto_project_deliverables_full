
# Cryptocurrency Price Prediction with LSTM (2023–2025)

This project collects historical price data and crypto-related news titles for the top 10 cryptocurrencies in 2023 and 2024, performs sentiment analysis, and trains an LSTM model to predict prices for 2025.

## Objective

- Collect historical **price data** for top 10 cryptocurrencies from 2023–2024
- Collect **crypto news titles**
- Perform **data cleaning**, **EDA**, and **sentiment analysis**
- Train a **machine learning model** (LSTM) to predict prices for 2025
- **Visualize results** and export predictions

## Data Sources

- Price data from [Twelve Data API](https://twelvedata.com/)
- News data from [CryptoCompare News API](https://min-api.cryptocompare.com/data/v2/news/)

## Project Structure

- `crypto_price_prediction.ipynb` – main notebook with code and visualizations
- `*_historical_data.csv` – cleaned historical price datasets
- `crypto_project_deliverables.zip` – full archive with notebook and CSVs

## Model

- Long Short-Term Memory (LSTM) neural network
- Trained on BTC/USD historical data
- Predicts closing prices for each day in 2025

## Results

- Sentiment analysis performed using TextBlob
- LSTM model predicts BTC/USD prices for 2025
- Visual plots included for analysis

## Requirements

```bash
pip install requests pandas matplotlib scikit-learn textblob tensorflow
```

## How to Run

1. Clone the repo or download the ZIP
2. Install dependencies
3. Run `crypto_price_prediction.ipynb` in Jupyter
4. View plots and predictions

## License

MIT License
