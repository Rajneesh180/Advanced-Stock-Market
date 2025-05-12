# NASDAQ-Tech-Stock-Prediction-Forecasting 📈💻

## 📊 Project Overview

Welcome to the **NASDAQ-Tech-Stock-Prediction-Forecasting** repository! 🚀 This project focuses on predicting the **short-term stock prices** of leading tech companies listed on **NASDAQ**, such as **Apple, Google, Microsoft**, and **Amazon**. The forecasting model leverages **Long Short-Term Memory (LSTM)** networks 🧠, a powerful type of Recurrent Neural Network (RNN) designed for time series forecasting.

Additionally, this model integrates **sentiment analysis** using **VADER** to include real-time news and social media sentiment, enhancing prediction accuracy. The project also features a **real-time web application** to visualize stock price predictions for easy access by both individual and institutional investors.

---

## 🚀 Key Features

* **LSTM-based Deep Learning** for short-term stock price forecasting 📉
* **Sentiment Analysis** using VADER from real-time news and social media 💬
* **Real-time Web Application** for interactive stock prediction 🌐
* **Performance**: Achieves a **MAPE of 2.72%** on unseen test data 🎯
* Comparison with **ARIMA** and other classical models showing superior accuracy 📊

---

## 🔧 Requirements

Before running the project, make sure you have the following dependencies installed:

* Python 3.7+
* Libraries:

  * `TensorFlow` for LSTM model training 🧠
  * `Pandas` for data manipulation 🗃️
  * `Numpy` for numerical computations ➗
  * `matplotlib` for plotting graphs 📊
  * `streamlit` for the web application 🌍
  * `joblib` for loading the trained model 🔐
  * `VADER` for sentiment analysis 🧑‍💻

To install the required libraries, you can use:

```bash
pip install -r requirements.txt
```

---

## 🛠️ How to Run

1. Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/NASDAQ-Tech-Stock-Prediction-Forecasting.git
```

2. Navigate to the project folder:

```bash
cd NASDAQ-Tech-Stock-Prediction-Forecasting
```

3. Run the Streamlit app to start the web interface:

```bash
streamlit run app.py
```

4. Enter a stock message, click **"Predict"**, and view the stock prediction in real-time! 📈

---

## 🧑‍💻 How it Works

* **Data Collection**: Historical stock data of **Apple**, **Google**, **Microsoft**, and **Amazon** are collected from **Yahoo Finance**.
* **Preprocessing**: Data is preprocessed, including **normalization** and **feature engineering**.
* **Model**: The **LSTM model** learns temporal patterns in the stock price data to forecast future prices.
* **Sentiment Analysis**: The model also incorporates sentiment data from **VADER** based on real-time **news articles** and **social media** posts to further refine predictions.
* **Prediction**: The trained model predicts future stock prices, and the web interface displays results dynamically.

---

## 📈 Example Output

Once you input a tech stock's ticker (e.g., AAPL, GOOG, MSFT, AMZN) in the web application, the model will:

Forecast Future Stock Price: The LSTM model will predict the stock price for the next few days based on historical data 📅.

Visualize Predictions: The predicted stock prices will be plotted on a graph, allowing users to compare the forecasted prices with actual historical prices 📊.

Real-Time Updates: The application will fetch real-time stock data and incorporate sentiment analysis from recent news and social media to adjust predictions dynamically 📰.

The interactive web interface allows users to explore the predicted future stock price trends, giving them insights into potential investment opportunities! 🚀

---

## 🤝 Contributing

We welcome contributions to make this project even better! If you'd like to improve the model, add new features, or fix bugs, feel free to fork the repository, create a branch, and submit a pull request! 🎉

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. ⚖️

---

## 🌟 Acknowledgments

* Thanks to **Yahoo Finance** for providing stock data 📉
* Special mention to the **VADER Sentiment Analysis** tool for enhancing the prediction accuracy 📚
* The project uses the **TensorFlow** library to train the LSTM model 🧠

---

Hope this helps! Enjoy exploring and predicting NASDAQ Tech stocks! 🚀📈
