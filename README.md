# Asset Price Prediction

This project predicts the prices of various assets like Bitcoin, Gold, and Brent Oil using historical price data and sentiment analysis of world news headlines. It utilizes Long Short-Term Memory (LSTM) neural networks to forecast future price movements.

## Features

* **Time Series Forecasting:** Employs LSTM models, a type of recurrent neural network (RNN), for time series prediction.
* **Sentiment Analysis:** Incorporates sentiment analysis of daily world news headlines to capture market sentiment.
* **Multiple Assets:** Includes dedicated Jupyter Notebooks for predicting the prices of Bitcoin, Gold, and Brent Oil.
* **Comprehensive Analysis:** The notebooks cover data loading, preprocessing, feature engineering, model training, and evaluation.

## Datasets

The project uses the following datasets:

* `WorldNewsData.csv`: Contains the top 25 daily news headlines from May 2018 to June 2019.
* `Bitcoin.csv`: Historical daily price data for Bitcoin.
* `XAU_USD.csv`: Historical daily price data for Gold.
* `Brent_Oil.csv`: Historical daily price data for Brent Oil.

## Prerequisites

The following libraries are required to run the project:

* pandas
* numpy
* matplotlib
* scikit-learn
* tensorflow
* nltk
* sentence-transformers

## Installation

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow nltk sentence-transformers