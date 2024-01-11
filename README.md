# Stock Trend Prediction with LSTM
This project leverages a Long Short-Term Memory (LSTM) neural network implemented using the Keras library for predicting stock trends. The LSTM model is constructed with layers featuring various units and dropout regularization to capture complex temporal patterns in historical stock data.

# Key Components:
# Model Architecture: 
The LSTM model is configured with multiple layers to effectively capture sequential patterns in stock data.
Optimization: The Adam optimizer is utilized for efficient model training, and the mean squared error loss function is employed for regression tasks.
# Data Collection: 
The yfinance library is employed to scrape historical stock data from Yahoo Finance, providing a diverse and dynamic dataset for training the model.
# Deployment with Streamlit:
The interactive web application is deployed using Streamlit, enabling users to visualize and explore stock trend predictions. Users can input custom stock symbols and observe the model's predictions in real-time, fostering a user-friendly and accessible platform for stock analysis.

# Instructions for Running the Application:
Ensure that Python and the necessary libraries are installed.
Clone the repository and navigate to the project directory.
Run streamlit run app.py to launch the web application locally.
Input desired stock symbols and explore the model's predictions.

Explore the power of LSTM-based stock trend prediction with this intuitive and interactive Streamlit app.
