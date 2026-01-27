# GDG_AIML_PS

## Task 1 – Predictive Core (Time Series Forecasting)

### Objective  
Build a forecasting engine that learns from historical stock data and predicts future prices with uncertainty estimation.

### Implementation

- Historical stock data collected using Yahoo Finance.
- Data normalized using MinMaxScaler.
- Sliding window sequence generation.
- LSTM-based deep learning model.
- Monte Carlo Dropout for uncertainty modeling.
- Rolling forecast validation.
- Performance metrics:
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)

### Output

- Historical stock price graph.
- Future forecast plot.
- Confidence interval (uncertainty band).
- Printed accuracy metrics.

### Technologies Used

- TensorFlow / Keras  
- LSTM Neural Networks  
- NumPy, Pandas  
- Scikit-learn  
- Matplotlib  
- yFinance  

---

## Task 2 – Analytical Chatbot (RAG & Explanation)

### Objective  
Create a natural language chatbot that explains stock market movements using semantic understanding and news sentiment.

### Implementation

- Semantic query understanding using Sentence Transformers.
- Vector database created using FAISS.
- Ticker extraction using embedding similarity.
- Stock trend analysis using percentage returns.
- Financial news retrieval via Google News RSS.
- Sentiment analysis using FinBERT.
- Explainable response generation.
- Stock price visualization with chatbot output.

### Capabilities

The chatbot can answer queries like:
- "Why did Steve Jobs’ company crash?"
- "Reason behind Microsoft stock fall?"
- "When did Tesla go up?"

And explains using:
- Stock price trends.
- News sentiment.
- Key financial headlines.

### Technologies Used

- Hugging Face Transformers  
- FinBERT (ProsusAI)  
- Sentence Transformers  
- FAISS (Vector Database)  
- Feedparser  
- yFinance  
- Matplotlib  

---

## Task 3 – Real-Time Intelligence (Live Data Integration)

### Objective  
Enable real-time stock monitoring with live price updates and alert triggers.

### Implementation

- Historical data backfill for 7 days.
- Live data streaming via Binance WebSocket.
- Real-time price ingestion.
- Interactive dashboard using Plotly.
- Dynamic alerts for price thresholds.
- Continuous dashboard refresh.

### Features

- Real-time BTC price tracking.
- WebSocket-based streaming.
- No page refresh required.
- Live visualization.
- Upper and lower threshold alerts.

### Technologies Used

- WebSocket Client  
- Binance Streaming API  
- Plotly  
- Pandas  
- yFinance  

---



