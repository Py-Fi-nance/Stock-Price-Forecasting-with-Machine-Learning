# Stock Price Forecasting using Machine Learning

This repository contains Python code for stock price prediction using various Machine Learning models. We aim to forecast the closing price of Apple Inc. (AAPL) stock leveraging historical stock data and different machine-learning algorithms.

![Python Version](https://img.shields.io/badge/Python-3.6%2B-blue)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![Forks](https://img.shields.io/github/forks/Py-Fi-nance/Stock-Price-Forecasting-with-Machine-Learning)](https://github.com/Py-Fi-nance/Stock-Price-Forecasting-with-Machine-Learning/network)
[![Stars](https://img.shields.io/github/stars/Py-Fi-nance/Stock-Price-Forecasting-with-Machine-Learning)](https://github.com/Py-Fi-nance/Stock-Price-Forecasting-with-Machine-Learning/stargazers)

## Table of Contents
1. [Dataset](#dataset)
2. [Model Overview](#model-overview)
3. [Model Evaluation and Results](#model-evaluation-and-results)
4. [Getting Started](#getting-started)
5. [Acknowledgments](#acknowledgments)

## Dataset <a name="dataset"></a>

The dataset used in this project, named 'AAPL_short_volume.csv', is extracted from OpenBB, a prominent open-source investment analysis company. The dataset consists of historical closing prices of AAPL stock, which will be used for training and evaluating our machine-learning models. The 'AAPL_short_volume.csv' file can be found in the "data" directory of this repository.

## Model Overview <a name="model-overview"></a>

Several machine learning models are implemented for stock price forecasting, including:

- LSTM (Long Short-Term Memory) model
- Support Vector Machines (SVM) model 
- Random Forest model 
- Gradient Boosting methods (XGBoost and LightGBM)

These models will be trained on the historical stock price data to predict future stock closing prices.

## Model Evaluation and Results <a name="model-evaluation-and-results"></a>

To evaluate the performance of each model, we use the **Root Mean Square Error (RMSE)** metric. The lower the RMSE value, the more accurate the model's predictions are. After evaluating all models, we found that the LSTM model demonstrates superior predictive performance, achieving the lowest RMSE compared to the other models. This highlights the strength and effectiveness of the LSTM model in accurately forecasting stock prices.

## Getting Started <a name="getting-started"></a>

To run the code and reproduce the results:

1. Clone this repository to your local machine.
2. Ensure you have Python installed (Python 3.x recommended) along with the necessary libraries.

## Acknowledgments <a name="acknowledgments"></a>

We would like to express our sincere gratitude to OpenBB, a leading open-source investment analysis company, for providing the invaluable dataset used in this research project. For any questions or inquiries, please contact support@pyfi.com - Subject: Github Repo Q, Stock Prediction using Machine Learning

For a full article walkthrough, please visit [our blog](https://www.pyfi.com/blog/stock-price-forecasting-machine-learning) and learn more about PyFi's award winning Python for Finance courses which have been trusted by the top financial institutions in the United States and Canada multiple years running here >> https://www.pyfi.com << 

[![Follow on LinkedIn](https://img.shields.io/badge/Follow%20on-LinkedIn-blue?style=social&logo=linkedin)](https://www.linkedin.com/company/pyfi/)
