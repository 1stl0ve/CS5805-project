# Comparing Machine Learning Models for Stock Market Price Prediction

**CS 5805: Machine Learning Final Project**

Pranesh Ambokar, Mohammad Heydari, Roshan Ravindran, and Leo St. Amour

## Overview

This project analyzes and compares the performance characteristics and prediction accuracy trade-offs of linear regression and long short-term memory (LSTM) when applied to stock market prediction.
We train the models using historical stock data and ask them to predict a stock's closing price given its opening, low, and high prices.

## Structure

- Code: all of the code can be found in `project.ipynb`.
- Data: the data is located in the `large_cap` and `mid_cap` directories.
The directories contain 50 large-cap and 50 mid-cap stocks, respectively.
- Saved data: the trained LSTM model is saved as `lstm_trained.keras`.
The `kt_dir` directory contains cache files for LSTM hyper-parameter fine-tuning.
The `graphs` directory contains saved versions of accuracy and day-trading simulation graphs.

## Running the Code

To run the code, install any necessary dependencies:


```
$ python3 -m pip install numpy pandas matplotlib scikit-learn tensorflow keras_tuner
```

Then open the project using Jupyter, or a comparable system, and execute each cell in order.

NOTE: the final two cells, which execute the day trading simulation for linear regression and LSTM, take approximately 10 minutes and 1 hour, respectively, to execute.
