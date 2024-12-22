# Stock Price Prediction

This project involves predicting the stock prices of Microsoft Corporation using historical data from 2001 to 2021. The model employs a **Long Short-Term Memory (LSTM)** network to forecast the stock price of the next day based on the data of the previous 50 days.

## Features

**Historical Data:** Microsoft stock data spanning 20 years (2001-2021).

**Deep Learning Model:** Implementation of an LSTM network, a powerful neural network model for sequence prediction tasks.

**Windowed Prediction:** Utilizes the past 50 days of stock prices to predict the next day's price.

## Project Structure

**Data:** Contains the dataset of Microsoft's historical stock prices.

**Preprocessing:** Steps include scaling data, creating sequences, and splitting the data into training and testing sets.

**Model:** The LSTM model is implemented with layers for input, LSTM cells, and dense output.

**Evaluation:** Model performance is evaluated using metrics like Mean Squared Error (MSE).

**Visualization:** Results are visualized to compare predicted prices with actual prices.

## Requirements

Python 3.7+

**Libraries:**

numpy

pandas

matplotlib

scikit-learn

tensorflow/keras

## Usage

**Prepare the Environment:** Ensure the required libraries are installed.

**Load Data:** Import the historical stock price dataset.

**Run the Script:** Execute the main Python script to train the LSTM model and generate predictions.

**View Results:** Analyze the predicted vs. actual stock prices through the visualizations.

## Results

The LSTM model effectively captures the trends in Microsoft's stock prices over time.

Prediction accuracy is demonstrated through visual plots comparing predicted and actual stock prices.
