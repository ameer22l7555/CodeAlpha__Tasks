# CodeAlpha__Tasks


# Task 1: Titanic Classification
Objective: Create a classification system to predict whether a person would survive the Titanic sinking based on socio-economic status, age, gender, and other factors.

Steps:

Load and Explore the Dataset:

Import necessary libraries.
Load the Titanic dataset.
Inspect the first few rows of the dataset.
Preprocess the Data:

Handle missing values:
Fill missing Age values with the median.
Drop the Cabin column due to a high number of missing values.
Fill missing Embarked values with the mode.
Encode categorical variables (Sex and Embarked).
Select relevant features for the model (Pclass, Sex, Age, SibSp, Parch, Fare, Embarked).
Split the Data:

Split the dataset into training and testing sets.
Train a Machine Learning Model:

Use a Random Forest classifier.
Train the model on the training data.
Evaluate the Model:

Make predictions on the test data.
Evaluate the model's performance using metrics like accuracy, classification report, and confusion matrix.


# Task 2: Stock Price Prediction using LSTM
Objective: Predict the stock price of any company using an LSTM model.

Steps:

Import Libraries:

Import necessary libraries like pandas, numpy, matplotlib, MinMaxScaler, Sequential, and LSTM.
Download and Load the Dataset:

Use the yfinance library to download stock price data.
Load the dataset and inspect the first few rows.
Preprocess the Data:

Filter the dataset to use only the Close price.
Scale the data using MinMaxScaler.
Split the data into training and test sets.
Create sequences of 60 days of data for training the LSTM.
Build and Train the LSTM Model:

Build an LSTM model using Sequential.
Add LSTM layers and Dense layers.
Compile and train the model.
Make Predictions:

Prepare the test data.
Make predictions using the trained model.
Inverse transform the scaled predictions.
Evaluate the Model:

Calculate the RMSE (Root Mean Squared Error).
Plot the training and predicted stock prices for visualization.
