# Stock Price Prediction

A Deep Learning Approach for Stock Price Prediction and Trend Capturing by [Telmo Linacisoro](https://github.com/telmolinacisoro) and [José Pérez](https://github.com/jopecl)

In this repository, you will find three different approaches for solving stock price predictions:

1. **LSTM based** using a single label as a target.
2. **CNN and LSTM based** using a single label as a target.
3. **LSTM based** using a multi-label as a target.

Additionally, you will find some example data publicly obtained from Kaggle, a comparison between the different models and hyperparameters, and the papers on which the model architecture was based.

We achieved a maximum accuracy of 95.92%, considering predictions within a tolerance of ±0.1 as correct. Moreover, using the multi-label approach, we captured trends up to 30 days into the future, which can be used to implement further technical analysis.

Everything can be run from Google Colab by downloading the data and adjusting your path in the notebooks.
