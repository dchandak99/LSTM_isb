# LSTM_with_attention_for_time_series

This project was done while I was an intern at ISB Hyderabad during December 2019 and Jnauray 2020.

### Deep Learning: Applying NLP techniques to Time Series Analysis for Stock Futures 

**Highlights:**

- Designed and implemented an intuitive approach to storing the history of a stock in the form of a vector using a Ticker Embedding Model, similar to that in a Word Embedding model
- Incorporated a number of technical indicators such as Momentum, Trailing Volatility, Asset Class and average return across each asset class along with these embeddings for time series analysis
- Designed, trained and tested an **LSTM** classifier (built using **PyTorch**) on a time series of multiple stock tickers to predict the Expected Return and to study non linearity and inter asset class correlation
- Expanded the base LSTM to incorporate **attention**, and retrain over the latest data while testing
- Optimized the hyperparameters using libraries: Ray for **Grid Search** and Hyperopt for **Bayesian** optimization
