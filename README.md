# GNN
Using some RNN Variant Models for predicting Stock Price Market

# DATASET
The dataset used for training and evaluation is historical stock price data. The research is conducted on the VanEck Vietnam 
ETF (VNM) Dataset recored from 31/12/2018 to 30/11/2022 of 988 observation.

# MODELS
Three different models have been implemented for stock price prediction:

*LSTM with Attention: This model combines the long short-term memory (LSTM) architecture with an attention mechanism to capture important temporal dependencies and focus on relevant information while making predictions.

*Bidirectional LSTM: This model incorporates both forward and backward information by using two separate LSTM layers, allowing the model to capture dependencies from both past and future time steps.

*GRU (Gated Recurrent Unit): The GRU model is a variation of the LSTM architecture that simplifies the network structure while still capturing long-term dependencies. It is known for its efficiency and effectiveness in sequence modeling tasks.

# USAGE
To use these models for stock price prediction, follow these steps:

*Install the required dependencies by running pip install -r requirements.txt.

*Prepare your dataset by ensuring it follows the same format as the provided sample data.

*Split the dataset into training and testing sets.

*Run the appropriate model script (lstm_attention.ipynb, bidirectional_lstm.ipynb, or gru_model.ipynb) and provide the necessary input arguments such as the path to the training and testing data.

*The model will be trained on the training data and evaluate its performance on the testing data. The predicted stock prices will be generated as output.

*Analyze the performance metrics and visualize the predicted stock prices using the provided plotting functions.

# RESULT
The performance of each model can be evaluated using various metrics such as mean absolute percentage error(MAPE), root mean squared error (RMSE), and mean absolute error (MAE). Additionally, visualizations can be generated to compare the predicted stock prices with the actual prices.

# CONCLUSION
By comparing the performance of LSTM with Attention, Bidirectional LSTM, and GRU models, we can gain insights into their effectiveness in predicting stock prices. This project serves as a starting point for further research and experimentation with deep learning architectures in the field of stock price forecasting.

Please refer to the individual model scripts and documentation for more details on each model's implementation and usage.
