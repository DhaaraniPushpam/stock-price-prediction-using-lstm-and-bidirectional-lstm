# 📈 Stock Price Prediction using LSTM & Bidirectional LSTM

Predicting future stock prices using deep learning time-series models — comparing standard LSTM vs Bidirectional LSTM performance on real market data.

## 🛠️ Tech Stack
- **Python 3.x** — core language
- **TensorFlow / Keras** — LSTM and BiLSTM model architecture
- **Pandas & NumPy** — data manipulation and preprocessing
- **Matplotlib / Seaborn** — visualization of predictions vs actuals
- **Scikit-learn** — MinMaxScaler for data normalization
- **Jupyter Notebook** — interactive development and analysis

## 📌 What It Does
- Fetches and preprocesses historical stock price data (OHLCV format)
- Normalizes time-series data using MinMaxScaler for stable training
- Builds and trains a standard **LSTM** model for sequential prediction
- Builds and trains a **Bidirectional LSTM** model to capture both past and future context
- Compares both models using RMSE and MAE evaluation metrics
- Visualizes predicted vs actual prices with confidence intervals

## 🧠 Key Concepts Demonstrated
- Time-series windowing (sequence length, look-back period)
- Vanishing gradient problem and how LSTM solves it
- Bidirectional processing — why it captures more temporal context
- Overfitting prevention: Dropout layers, Early Stopping

## 🚀 How to Run
```bash
git clone https://github.com/DhaaraniPushpam/stock-price-prediction-using-lstm-and-bidirectional-lstm
cd stock-price-prediction-using-lstm-and-bidirectional-lstm
pip install tensorflow pandas numpy matplotlib scikit-learn jupyter
jupyter notebook
```
Open the `.ipynb` file and run all cells sequentially.

## 📊 Model Comparison

| Model | RMSE | MAE |
|---|---|---|
| LSTM | — | — |
| Bidirectional LSTM | — | — |

> Update this table with your actual results after running the notebook.

## 🔍 Sample Output
The model outputs a chart overlaying predicted stock prices against actual closing prices across the test period, showing how closely the model tracks real market movement.

## 📚 What I Learned
- How LSTMs handle long-range dependencies in sequential data
- The computational trade-off of Bidirectional vs standard LSTM
- Real-world challenges: data leakage, look-ahead bias in financial ML

---
*Built as part of data science internship work and independent ML research.*
