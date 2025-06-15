# Stock Price Analysis using LSTM

This project analyzes and predicts stock prices of major tech companies — **Apple (AAPL), Google (GOOG), Microsoft (MSFT), and Amazon (AMZN)** — using historical data and a deep learning LSTM model.

---

## Tools Used

* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **yFinance**
* **Keras (TensorFlow backend)**
* **scikit-learn**

---

## What This Project Does

* Downloads stock data using **yFinance**
* Plots:

  * Closing prices
  * Moving averages (10, 20, 50 days)
  * Daily returns
  * Return correlations
* Builds an **LSTM model** to predict Apple’s stock price
* Compares predicted vs actual prices

---

## How to Run

1. **Clone this repo**

```bash
git clone https://github.com/yourusername/tech-stock-lstm.git
cd tech-stock-lstm
```

2. **Install dependencies**

```bash
pip install yfinance pandas matplotlib seaborn scikit-learn keras tensorflow
```

3. **Run the script**

```bash
python stock_prediction_lstm.py
```

Or use Jupyter Notebook to explore it step by step.

---

## Output

* Line plots of stock prices
* Histograms of daily returns
* Correlation heatmaps
* A graph comparing predicted and actual Apple stock prices

---

## Disclaimer

This project is for learning purposes only. Do not use it for real investment decisions.

## Author
* Sarvam Saroha
* 🔗 www.linkedin.com/sarvamsaroha
* 📧 Email


