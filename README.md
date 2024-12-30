# Stock Market Predictor
## Overview
A web-based stock market prediction application utilizing machine learning and technical analysis. Built with Streamlit, Keras, and yfinance.

## Features
- Predicts stock prices using a pre-trained Keras model
- Visualizes original vs predicted prices
- Displays moving averages (MA50, MA100, MA200) for technical analysis
- User input for stock symbol

## Requirements
- Python 3.x
- Streamlit
- Keras
- yfinance
- NumPy
- Pandas
- Matplotlib

## Usage
1. Clone the repository:
    ```sh
    git clone https://github.com/Anujsinghchaudhary/Stock-prediction-model.git
    ```
2. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```
3. Run the application:
    ```sh
    streamlit run app.py
    ```
4. Access the web application at [http://localhost:8501](http://localhost:8501).

## Model Details
- Pre-trained Keras model (`Stock Predictions Model.keras`)
- Trained on historical stock data
- Uses Min-Max Scaler for data normalization