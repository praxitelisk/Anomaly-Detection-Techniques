# Anomaly-Detection-Techniques

Hello everybody! In this Jupyter notebook I am reviewing all the anomaly detection techniques that are commonly used in Data Science. Mostly used the following techniques:

1. Statistical Methods:
   - Z-score: Detect anomalies based on the number of standard deviations away from the mean.
   - Modified Z-score: A variation of Z-score that is robust to outliers.
   - Percentiles: Identify anomalies based on data points falling outside a specified percentile range.
   - Grubbs' Test: Detect outliers in a univariate dataset based on extreme values.


2. Density-Based Methods:
   - Local Outlier Factor (LOF): Measures the local density deviation of a data point with respect to its neighbors.
   - DBSCAN (Density-Based Spatial Clustering of Applications with Noise): Clusters the data and labels points with low-density neighborhoods as outliers.
   

3. Distance-Based Methods:
   - k-Nearest Neighbors (k-NN): Assign anomalies based on the distance to their k-nearest neighbors.
   - Mahalanobis Distance: Measures the distance between a data point and the center of a distribution, accounting for the covariance between variables.


4. Machine Learning-Based Methods:
   - One-Class SVM (Support Vector Machine): Trains a model on normal data and identifies deviations as anomalies.
   - Autoencoders: Unsupervised neural network models that learn to reconstruct normal data and flag deviations as anomalies.
   - Isolation Forest: Builds an ensemble of isolation trees to isolate anomalies.
   

5. Time Series Anomaly Detection:
   - Moving Averages: Apply a moving average to smooth out noise in the time series. Anomalies are detected based on the deviation from the moving average.
   - Seasonal Decomposition: Decompose a time series into its components (trend, seasonality, and residual). Anomalies can be detected in the residual component.
   - Exponential Smoothing: Forecasts future values and identifies anomalies based on deviations from the forecasted values.
   - ARIMA (AutoRegressive Integrated Moving Average): Fit an ARIMA model to the time series data and compare the residuals to detect anomalies.
   - LSTM Autoencoders: Uses Long Short-Term Memory networks to detect anomalies in sequential data.
