# 📈 Stock Prediction Using LSTM

This project demonstrates a Python-based solution for forecasting stock prices of major food industry companies—**Tata Consumer Products**, **Hindustan Unilever**, **Nestle India**, **Britannia**, and **ITC**—over a short-term horizon. It utilizes **time-series analysis** techniques to generate predictions based on historical stock data, offering users valuable insights into potential future trends. The application integrates **real-time market data** using `yfinance` and delivers a **visual and interactive interface** through **Streamlit**, making it accessible to both technical and non-technical users.

---

## 🔍 Key Features

### 🧠 Forecasting with LSTM (Long Short-Term Memory) Networks
- Utilizes LSTM, a type of Recurrent Neural Network (RNN) ideal for sequential and time-series data.
- Captures both short-term and long-term trends in stock market patterns using historical data.
- The model is trained on closing prices and evaluated for prediction accuracy over a rolling 10-day window.

### 📊 Live Market Data via Yfinance
- Implements the **`yfinance`** library to fetch **real-time stock data** from Yahoo Finance.
- Users can stream the most recent market data before making predictions.
- Historical stock data is used to train and update the model dynamically.

### 🌐 Interactive Web App with Streamlit
- Deployed using **Streamlit**, allowing users to:
  - Select a stock.
  - View historical and real-time data.
  - Visualize model predictions with interactive plots.
- No need for web development experience—just run the app and start predicting!

---

## 🧰 Technologies Used

| Technology     | Purpose                                                                 |
|----------------|-------------------------------------------------------------------------|
| Python         | Core programming language for data processing and application logic     |
| Pandas         | Data manipulation and analysis, especially for time-series stock data   |
| NumPy          | Numerical operations and support for arrays/matrices                    |
| Matplotlib     | Basic visualization of historical stock trends                          |
| yfinance       | Fetches real-time and historical stock market data from Yahoo Finance   |
| Streamlit      | Creates an interactive and user-friendly web app interface              |
| scikit-learn   | Basic preprocessing and data scaling utilities                          |

---

## 🚀 Getting Started

To set up and run the **Stock Prediction** application locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shruti1632/StockPrediction.git
   cd StockPrediction
   ```

2. **Install dependencies**:
   Ensure you have Python installed. Then, install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**:
   ```bash
   streamlit run StocksPrediction.py
   ```

   This will launch the Streamlit web application in your default browser.

---

## 📁 Repository Structure

- `StocksPrediction.py`: Main script containing the Streamlit application and LSTM model implementation.
- `README.md`: Documentation and overview of the project.
- `LICENSE`: MIT License file for the project.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙋‍♀️ Author

**Shruti Pawar**

- [GitHub](https://github.com/Shruti1632)
- [LinkedIn](https://www.linkedin.com/in/shruti-pawar-0a9031235/)

---
