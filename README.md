**Stock Analysis Repository**
This repository contains Jupyter notebooks that perform the following tasks:

Data Collection: Download historical stock data for companies like NVDA, AAPL, AMZN, and GOOG using the Yahoo Finance API.

Data Preprocessing: Clean and normalize the data to prepare it for training. This includes feature engineering, scaling values using MinMaxScaler, and creating sequences for time series analysis.

Model Training: Train an LSTM model to predict future stock prices based on historical data.

Prediction and Evaluation: Predict stock prices for the given companies, visualize the predictions against the actual data, and evaluate model performance using RMSE (Root Mean Squared Error).

Visualization: Plot actual vs. predicted stock prices for easy comparison and analysis.

**Dependencies**

To run the notebooks in this repository, you will need the following Python libraries:

pandas: For data manipulation and analysis.

numpy: For numerical operations.

matplotlib: For visualizing stock trends and predictions.

yfinance: To fetch historical stock data from Yahoo Finance.

tensorflow and keras: To build and train the LSTM model.

sklearn: For data preprocessing (e.g., MinMaxScaler).

You can install the required dependencies using the following command:
pip install pandas numpy matplotlib yfinance tensorflow scikit-learn
