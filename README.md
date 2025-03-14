# End to End Stock Price Prediction with BiLSTM, Flask, and React

## Overview

This project is a stock price visualization and prediction tool that integrates machine learning, Flask, Alpha Vantage API, React, and Firebase OAuth authentication. The model utilizes a Bidirectional Long Short-Term Memory (BiLSTM) neural network to forecast future stock prices based on historical data.

## Features

### Stock Data Collection:  Uses the Alpha Vantage API to fetch monthly adjusted stock prices.

### Machine Learning Prediction: Predicts future stock prices using a trained BiLSTM model.

### Interactive Chart: Displays stock trends using a responsive Recharts line chart.

### User Authentication: Google sign-in enabled with Firebase OAuth.

### Backup Local Data: Uses a local dataset (data.json) when API calls fail.

## Tech Stack

Frontend: React.js, Firebase Authentication, Recharts

Backend: Flask, TensorFlow/Keras, Alpha Vantage API

Database: JSON (Local), Alpha Vantage API (Live Data)

Authentication: Firebase OAuth

## Why BiLSTM?

1. Better Context Understanding: Since it processes stock price trends in both past and future directions, it learns patterns more efficiently.

2. Enhanced Predictive Accuracy: By considering both historical and future trends, the model improves prediction reliability.

3. Effective for Sequential Data: Stock prices follow sequential dependencies, making BiLSTM ideal for time-series forecasting.

## Usage

Sign In: Users must sign in with Google to access stock data.

View Stock Data: Displays historical stock prices in a line chart.

Predict Future Price: Uses BiLSTM to forecast the next month’s closing price.

Sign Out: Users can sign out at any time.
