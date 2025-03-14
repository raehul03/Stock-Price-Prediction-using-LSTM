Main Obsjective is to to design and implement an LSTM-based machine learning model to predict future stock prices based on historical data, leveraging the ability of LSTMs to capture long-term dependencies in sequential data.
LSTMs, a type of recurrent neural network (RNN), overcome this limitation by incorporating memory cells, making them ideal for tasks like stock price prediction where past trends influence future outcomes.
Dataset: Historical stock price data (e.g., from Yahoo Finance via yfinance library)
I have also used  Gated Recurrent Units (GRUs). GRUs are simpler than LSTMs (using update and reset gates instead of forget, input, and output gates), which often leads to faster training times with comparable performance on many tasks.
