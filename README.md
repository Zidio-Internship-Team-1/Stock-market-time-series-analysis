
# Stock Market Time Series Analysis

This repository provides an advanced toolkit for stock market time series analysis and forecasting, leveraging statistical, classical machine learning, and deep learning techniques. The project is designed for robust experimentation and visualization of stock price predictions using real-world datasets (like Apple Inc. - AAPL.csv).

## Table of Contents
- Features
- Project Structure
- Data
- Usage
- Requirements
- Models Implemented
- Visualization
- Acknowledgments

## Features

**Data Preprocessing & Feature Engineering:**
- Custom scripts to clean and engineer advanced features from raw stock data (moving averages, RSI, MACD, volatility, lag features, etc.).

**Forecasting Models:**
- ARIMA (with automatic parameter selection and diagnostics)
- Prophet (with custom seasonalities and regressors)
- LSTM Deep Learning (bidirectional layers, dropout, advanced architecture)
- Ensemble forecasts combining all models

**Visualization:**
- Plots for model diagnostics, prediction trends, and ensemble model comparison.

## Project Structure

*There may be additional files/folders. See the repository file browser for the full list.*

## Data

- **AAPL.csv**: Historical Apple stock prices (Date, Open, High, Low, Close, Adj Close, Volume).
- **cleaned_stock_market_data.csv**: Preprocessed version, ready for modeling.

## Usage

1. **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn statsmodels pmdarima prophet tensorflow
    ```
2. **Run the main pipeline:**
    ```bash
    python execution.py
    ```
    This will load data, engineer features, run ARIMA/Prophet/LSTM models, create ensemble forecasts, and generate visualizations.

3. **Explore the Jupyter Notebook:**  
   Open `Stock-market-data-analysis.ipynb` for step-by-step interactive analysis.

## Requirements

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels
- pmdarima
- prophet
- tensorflow

## Models Implemented

- **ARIMA:** Comprehensive ARIMA implementation with auto-parameter selection, stationarity checks, and diagnostics.
- **Prophet:** Facebook Prophet with additional seasonalities and custom regressors for market stress and volume surges.
- **LSTM:** Deep learning model using Keras/TensorFlow, with bidirectional layers and advanced callbacks.
- **Ensemble:** Weighted combination of ARIMA, Prophet, and LSTM predictions for robust future forecasts.

## Visualization

- Historical price plots with predictions
- Model comparison (ARIMA, Prophet, LSTM, Ensemble)
- Diagnostic plots (residuals, trend analysis)
- LSTM learning curves
- Accuracy summaries and more

## Acknowledgments

- Developed by the Zidio Internship Team 1.
- Data sourced from Yahoo Finance (AAPL).
- Uses open-source libraries: pandas, scikit-learn, statsmodels, Prophet, TensorFlow/Keras, matplotlib, seaborn, pmdarima.

---

*Note: This README is based on a partial file listing. For the full, latest details, visit the GitHub repository browser.*
