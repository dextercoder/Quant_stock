# Quant_stock
Stock analysis/prediction model using machine learning using the impact between different out-of-the-market factors (weather, etc.) and the stock prices.

---

![Architecture Diagram](Diagram.png?raw=true "Architecture Diagram")

## Models used
There are three ML model that are being implemented:
* A simple feedforward neural network
* A recurrent neural network with LSTM (long short term memory)
* A convolutional neural network

## Accuracy measurements
The pipeline implemented is using [backtrader](https://www.backtrader.com) to implement backtesting in order to test each individual strategy. In the future, it is worthwhile to try using a genetic algorithm to better figure the accuracy of the model.

## Usage
There are three main usages for this project: 

run `python driver.py -t model_name` to train

run `python driver.py -b model_name` to backtest the model
