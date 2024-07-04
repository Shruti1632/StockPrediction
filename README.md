# StockPrediction

This project involves the design and implementation of a model to forecast future values of leading food industry stocks, including Tata Consumer Products, Hindustan Unilever, Nestle India, Britannia, and ITC, over a 10-day horizon. The project employs advanced deep learning techniques and real-time data streaming to ensure accurate and up-to-date predictions.

# Key Features
- **Forecasting with Long Short-Term Memory (LSTM) Networks**: The core of this project is the use of LSTM networks, a type of recurrent neural network (RNN) known for its ability to capture long-term dependencies in sequential data. LSTMs are particularly well-suited for time series forecasting, making them ideal for predicting stock prices based on historical data.

- **Live Market Data with Yfinance**: To ensure that the model's predictions are as current as possible, Yfinance is utilized to gather and stream live market data. Yfinance is a powerful library that provides easy access to historical market data, allowing for real-time updates and analysis.

- **User-friendly Interface with Streamlit**: The project is deployed using Streamlit, a popular open-source app framework designed for machine learning and data science projects. Streamlit allows for the creation of interactive and user-friendly web applications with minimal effort. It is particularly useful for deploying machine learning models and visualizing data in real-time.

# Technologies Used
1. **Python**: The primary programming language used for developing the model and the application. Python is widely used in data science and machine learning due to its extensive libraries and ease of use.

2. **TensorFlow/Keras**: These libraries are used to build and train the LSTM network. TensorFlow is a comprehensive open-source platform for machine learning, and Keras is its high-level API that allows for easy and fast prototyping.

3. **Yfinance**: This library is used to fetch historical and real-time stock market data. It simplifies the process of accessing data from Yahoo Finance, making it easy to integrate live data streaming into the application.

4. **Streamlit**: An open-source app framework used to deploy the machine learning model as an interactive web application. Streamlit allows for the creation of custom web interfaces with simple Python scripts.

5. **Pandas**: A powerful data manipulation library in Python used for data preprocessing and analysis. It is essential for handling time series data and preparing it for model training.

6. **NumPy**: A fundamental library for numerical computing in Python. It provides support for arrays and matrices, along with a collection of mathematical functions to operate on these data structures.

# Deployment
The model was deployed using Streamlit, providing an interactive web interface where users can input parameters, view real-time stock data, and see the model's predictions. This deployment ensures that the application is accessible and easy to use, even for individuals without a deep understanding of machine learning.

For a detailed walkthrough of the implementation and to access the source code, visit the repository. This project is an excellent starting point for beginners interested in machine learning, stock price prediction, and deploying interactive web applications.
