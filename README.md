# Gold-Price-Forecasting
Time Series Forecasting of Gold Prices using historical market data

📌 Gold Price Forecasting using Prophet
📖 Project Overview

This project uses Facebook Prophet to forecast gold prices using historical time series data.
The objective is to analyze trends, seasonality, and evaluate forecasting performance on unseen data.

🛠️ Tech Stack

  Python
  Pandas
  Pandas
  Matplotlib
  Scikit-learn
  Prophet

📊 Workflow

Data preprocessing

  Train-Test split (80%-20%)
  
  Model training using Prophet
  
  Forecast generation
  
  Model evaluation (RMSE, MAE, R²)
  
  Trend & seasonality analysis
  
  1-year future forecasting

📈 Model Evaluation Results

  Metric	Value
  RMSE	91.7
  MAE	73.32
  R² Score	-1.098

📌 The model captured historical patterns but struggled during highly volatile periods, highlighting the difficulty of financial time series forecasting.

📉 Visualization Samples

  Train vs Test vs Prediction
  
  Trend & Seasonality Components
  
  1-Year Future Forecast

<img width="998" height="513" alt="image" src="https://github.com/user-attachments/assets/4a1cbf1d-f4a4-4e7e-9833-8198d6519353" />


🔍 Key Insights

  Prophet models smooth trends effectively
  
  Sudden market spikes are difficult to predict
  
  Financial forecasting requires handling volatility carefully

🚀 Future Improvements

   Hyperparameter tuning
  
  Log transformation
  
  Comparing with ARIMA / LSTM
  
  Adding external regressors (inflation, USD index)
