**Description:**
This repository contains Python code for stock price prediction using various Machine Learning models. The focus of this project is to forecast the closing price of Apple Inc. (AAPL) stock by leveraging historical stock data and applying different machine-learning algorithms.

**Dataset**
The dataset used in this project, named 'AAPL_short_volume.csv', is extracted from OpenBB, a prominent open-source investment analysis company. The dataset consists of historical closing prices of AAPL stock, which will be used for training and evaluating our machine-learning models. The 'AAPL_short_volume.csv' file can be found in the "data" directory of this repository.

**Model Overview**
Several machine learning models are implemented for stock price forecasting, including:
LSTM (Long Short-Term Memory) model
Support Vector Machines (SVM) model
Random Forest model
Gradient Boosting methods (XGBoost and LightGBM)
These models will be trained on the historical stock price data to predict future stock closing prices.

**Model Evaluation and Results**
To evaluate the performance of each model, we use the Root Mean Square Error (RMSE) metric. The lower the RMSE value, the more accurate the model's predictions are. After evaluating all models, we found that the
LSTM model demonstrates superior predictive performance, achieving the lowest Root Mean Square Error (RMSE) compared to the other models. This highlights the strength and effectiveness of the LSTM model in
accurately forecasting stock prices.

**Getting Started**
To run the code and reproduce the results:
Clone this repository to your local machine.
Ensure you have Python installed (Python 3.x recommended) along with the necessary libraries

**Acknowledgments**
We would like to express our sincere gratitude to OpenBB, a leading open-source investment analysis company, for providing the invaluable dataset used in this research project.

**License**
This project is licensed under the ....... Feel free to use, modify, and distribute the code for educational or research purposes.
For any questions or inquiries, please contact .........
