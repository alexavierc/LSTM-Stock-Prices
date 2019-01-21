# Predicting stock prices with LSTM network

This project goal is to demonstrate how to use LSTM networks and apply in some real data.

## Getting Started

In this repository, you will find the following notebook:
* Moving Average: First look at the data, a SMA and EMA model
* Sanity Check: A test with LSTM and the model used to make sure the model works
* LSTM input and output: An explanation on how I manipulated the data to use as input/output for the model
* LSTM Single Company: A LSTM model used to predict the closing price of a single company. Note that the notebooks ‘Single Company B’, ‘Single Company C’ and ‘Single Company D’ are extremely similar.
* LSTM multi-companies prediction: A LSTM model used to predict the closing price of all four companies (A, B, C and D).

### Prerequisites

The code was written in Python, and uses:
* Pandas and Numpy (for data manipulation)
* Matplotlib (for data visualisation)
* Keras (for building and training the model)
* sklearn (for data scaling)

## Results

A LSTM network is not able to predict the closing price behaviour by only looking at its historical data.