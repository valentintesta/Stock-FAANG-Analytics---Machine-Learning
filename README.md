# 📈 Stock FAANG Data App - Machine Learning
This project is an interactive web application that allows users to visualize and predict stock closing prices for FAANG companies (Google, Apple, Microsoft, GameStop). It is built using Python, Streamlit, Yahoo Finance, TensorFlow, and Matplotlib.

# 1️⃣ Downloading Financial Data
- The app uses yfinance to fetch historical stock data from 2015 to the present.
- The user can select a stock (GOOG, AAPL, MSFT, or GME) for visualization.


# 2️⃣ Data Visualization

## The latest rows of stock data are displayed

![raw data](https://github.com/user-attachments/assets/a380c59c-268f-4732-9dbd-c3b11d171a1a)

## Closing price charts


![Screenshot 2025-01-30 115017](https://github.com/user-attachments/assets/4c5a5fe0-baee-40aa-931e-723bb73558d9)


## Closing price: 100-day moving average (MA100)

![Screenshot 2025-01-30 115648](https://github.com/user-attachments/assets/114c8566-b665-44e5-9fb4-4314b5ea93d4)

## Closing price: 100-day and 200-day moving averages (MA100 & MA200)

![Screenshot 2025-01-30 115731](https://github.com/user-attachments/assets/4568a23c-4357-4007-ad03-1b136d0dae77)



3️⃣ Stock Price Prediction: Comparing Predictions vs. Actual Prices

- Data from the last 100 days is used to make predictions.

- Test data is formatted into input sequences for the neural network.

- Predictions are generated and inverse-transformed to match the original scale.

- A comparison graph is created to visualize actual stock prices vs. predicted prices.

![Screenshot 2025-01-30 120350](https://github.com/user-attachments/assets/c62b337f-f233-4d02-a634-3f3ea858daf4)
