# Bitcoin_price_prediction_with_LSTM
📌 Project Overview

This project aims to predict Bitcoin prices using a Long Short-Term Memory (LSTM) neural network. LSTMs are well-suited for time series forecasting as they can capture long-term dependencies in sequential data. The model is trained on historical Bitcoin price data and evaluates performance using various metrics. A Flask-based web interface is included to interact with the model.

🛠️ Tech Stack

Programming Language: Python
Backend: Flask
Frontend: HTML (index.html, result.html, base.html)
Libraries: TensorFlow/Keras, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, Flask
Dataset: Bitcoin historical price data (from sources like Yahoo Finance)

📊 Features

Data preprocessing (scaling, handling missing values, feature engineering)
LSTM model architecture for time series prediction
Flask-based web interface for user interaction
Data visualization (price trends, predictions vs actual values)

🚀 Installation

Clone the repository:
git clone https://github.com/yourusername/bitcoin-lstm-prediction.git
cd bitcoin-lstm-prediction

Create a virtual environment (optional but recommended):
python -m venv env
source env/bin/activate  # For macOS/Linux
env\Scripts\activate  # For Windows

Install dependencies:
pip install -r requirements.txt
Download Bitcoin historical price data from Yahoo Finance or another source.

📈 Model Architecture

Input Layer (LSTM)
Hidden Layers (Multiple LSTM + Dropout)
Dense Output Layer

📌 Future Enhancements

Hyperparameter tuning for improved accuracy
Adding other ML models for comparison
Deploying the model as a web app on a cloud platform

🤝 Contributing
Feel free to fork the repository, create a branch, and submit a pull request for improvements.
