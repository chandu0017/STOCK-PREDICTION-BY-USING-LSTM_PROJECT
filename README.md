# STOCK-PREDICTION-BY-USING-LSTM_PROJECT

Take stock price of any company you want and predicts its price by using LSTM. Use  Jupyter notebook or vscode.
Abstract : 
This project utilizes Long Short-Term Memory (LSTM) networks to predict stock prices based on historical closing data. After preprocessing the data and normalizing it for model training, sequences of past stock prices are fed into the LSTM model to forecast future prices. The model leverages its ability to capture long-term dependencies in time-series data. Results are evaluated by comparing actual and predicted prices, showcasing the effectiveness of LSTMs in financial forecasting despite market volatility.
Detailed explanation of the code :
1. Importing Libraries: We import the necessary libraries, including pandas for data manipulation, numpy for numerical operations, matplotlib for plotting, and keras for building the LSTM model.
2. Loading Data: We load the Apple stock price data from a CSV file.
3. Preprocessing Data: We set the date as the index, create a new dataframe with only the closing price, and convert the dataframe to a numpy array.
4. Scaling Data: We scale the data using the MinMaxScaler from sklearn to have values between 0 and 1.
5. Creating Training Data: We create the training data by splitting the scaled data into x_train and y_train. We use 80% of the data for training.
6. Reshaping Data: We reshape x_train and x_test to have a shape that can be fed into the LSTM model.
7. Building the LSTM Model: We create a Sequential LSTM model with two LSTM layers and two dense layers. We compile the model using the Adam optimizer and mean squared error loss function.
8. Training the Model: We train the model using the training data.
9. Making Predictions: We make predictions using the test data.
10. Plotting the Predictions: We plot the actual and predicted prices to visualize the performance of the model.




