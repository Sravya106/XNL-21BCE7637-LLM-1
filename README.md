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
