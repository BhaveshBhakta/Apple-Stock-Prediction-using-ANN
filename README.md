# Apple Stock Price Prediction Using LSTM

**Project Overview**  
This project aims to predict the future stock prices of Apple Inc. (AAPL) using Artificial Neural Networks (ANN). The stock market is highly volatile, and accurate predictions can be beneficial for investors and analysts. The model utilizes historical stock data, including features like opening price, closing price, high, low, and volume, to forecast future stock prices. The implementation involves data preparation, normalization, creating datasets, training an LSTM-based neural network, and evaluating its performance.

**Technical Highlights**  
- **Data Source**: Yahoo Finance API for downloading historical stock data.
- **Model Type**: Long Short-Term Memory (LSTM) network, a type of recurrent neural network (RNN) capable of learning sequential data patterns.
- **Libraries Used**: 
  - `pandas` for data manipulation.
  - `numpy` for numerical computations.
  - `matplotlib` and `seaborn` for data visualization.
  - `tensorflow` for building the ANN model.
  - `yfinance` for downloading stock data.
  - `sklearn.preprocessing` for data scaling (MinMaxScaler).
- **Performance Metrics**: The model’s performance is evaluated using Mean Squared Error (MSE) and accuracy.

**Purpose and Applications**  
The main purpose of this project is to provide a reliable stock price prediction model for Apple Inc. The model can assist investors, analysts, and traders in making informed decisions about their investments. The applications include:
- **Investment Decisions**: Helping investors predict the stock price trend.
- **Financial Analysis**: Assisting analysts in understanding market movements.
- **Trading Strategy**: Helping traders build strategies based on predicted prices.

**Installation**  
To set up and run this project locally, follow these steps:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/BhaveshBhakta/Apple-Stock-Prediction-using-ANN.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd Apple-Stock-Prediction-using-ANN
   ```
4. **Run the jupyter notebook**:

**Collaboration**  
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.
