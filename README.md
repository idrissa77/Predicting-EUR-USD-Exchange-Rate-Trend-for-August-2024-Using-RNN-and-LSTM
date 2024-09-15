EUR/USD Exchange Rate Trend Prediction

Project Overview:

In this project, we build a model based on Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) networks to forecast the trend of the EUR/USD exchange rate. We use five years of historical data from September 13, 2019, to September 13, 2024, which is downloadable from Investing.com.

The primary goal is to predict the trend for August 2024 and determine whether the EUR/USD rate will rise or fall.

Project Description:

This project involves:
1. Data Preprocessing: Scaling and preparing the data for training.
2. Model Building: Constructing an RNN-LSTM model to capture the time-series patterns in the EUR/USD exchange rate data.
3. Prediction: Using the model to forecast the EUR/USD rate for August 2024.
4. **Visualization: Plotting the predicted trends for August 2024 to visualize the forecasted rise or fall.

Data:

The data used in this project includes historical EUR/USD exchange rates from September 13, 2019, to September 13, 2024. The dataset can be downloaded from [Investing.com](https://www.investing.com).

- **Training Data:** Historical exchange rates up to August 2024.
- **Test Data:** Includes data for August 2024 and is used to validate the model.

## Model

The model is an LSTM-based RNN that includes:
- **Four LSTM Layers**: For capturing complex time-series patterns.
- **Dropout Layers**: To prevent overfitting.
- **Dense Output Layer**: To predict the future exchange rate.
