complete flow 
Collect IoT dataset (temperature, humidity, voltage, etc.).

Preprocess (handle missing values, scale data).

Create time-lag features (past 6h, 12h, 24h values).

Train baseline Random Forest/XGBoost.

Train advanced LSTM/GRU for time-series.

Evaluate → target 90%+ accuracy.

Deploy (e.g., Flask app showing prediction dashboard).
