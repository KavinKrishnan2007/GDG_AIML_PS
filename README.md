# GDG_AIML_PS
**Task 1 – Predictive Core (Time Series Forecasting)**
**Goal**
- Build a forecasting engine that predicts future stock prices while modeling uncertainty.
**What is implemented**
- Historical stock data from Yahoo Finance
- Data normalization using MinMaxScaler
- Sliding window sequence generation
- Deep Learning model using LSTM networks
- Monte Carlo Dropout for uncertainty estimation
- Rolling Forecast Validation
- Accuracy metrics:
    MAE (Mean Absolute Error)
    RMSE (Root Mean Squared Error)
**Key Features**
- Predicts future stock prices
- Evaluates real performance using rolling windows
- Generates confidence intervals
**Visualizes:**
- Historical trend
- Forecasted prices
- Uncertainty bands
**Technologies Used :** 
- TensorFlow / Keras
- LSTM Neural Networks
- NumPy, Pandas
- Scikit-learn
- Matplotlib
- yFinance
