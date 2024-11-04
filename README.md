Stock Market Predictor
Overview
A web-based stock market prediction application utilizing machine learning and technical analysis. Built with Streamlit, Keras, and yfinance.
Features
Predicts stock prices using a pre-trained Keras model
Visualizes original vs predicted prices
Displays moving averages (MA50, MA100, MA200) for technical analysis
User input for stock symbol
Requirements
Python 3.x
Streamlit
Keras
yfinance
NumPy
Pandas
Matplotlib
Usage
Clone the repository
Install dependencies (pip install -r requirements.txt)
Run the application (streamlit run app.py)
Access the web application at http://localhost:8501
Model Details
Pre-trained Keras model (Stock Predictions Model.keras)
Trained on historical stock data
Uses Min-Max Scaler for data normalization
You can simply run the model by-steamlit command in the terminal then entering the stock name from yahoo finance and model is ready to run
