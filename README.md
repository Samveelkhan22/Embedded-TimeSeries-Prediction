# Embedded-TimeSeries-Prediction
This project explores various time series prediction and classification techniques for univariate and multivariate data using RNN-based models. Each notebook demonstrates a different approach to forecasting and classifying time series data, using real-world datasets and optimizing for model performance.

## Project Objectives & Methods

### Q1. Univariate Time Series Forecast (Single-step)
- Develops an RNN model to predict the next value in a univariate time series dataset. Optimized for minimal Mean Squared Error (MSE) on the test data.

### Q2. Univariate Time Series Forecast (Multi-step)
- Extends the forecast to predict the next 10 values in the time series. The model is tuned to achieve low MSE across multiple time steps.

### Q3. Sequence-to-Sequence Multi-step Prediction
- Implements a sequence-to-sequence RNN to forecast the next 10 values at every timestep, resulting in more stable and efficient training and improved multi-step predictions.

### Q4. Time Series Classification
- Classifies time series data into binary categories (e.g., 'normal' or 'faulty') using models that leverage convolutional, dense, and recurrent layers for optimal accuracy.

### Q5. Multivariate Pollutant Prediction
- Uses a multi-output RNN to predict future concentrations of pollutants (CO, Benzene, and NOx) from multivariate time series data over multiple time steps.

## Requirements
To run these notebooks, install the following dependencies:

- numpy
- pandas
- tensorflow
- scikit-learn
- matplotlib

## Results
Each notebook provides metrics like MSE or accuracy, demonstrating model performance on the test set. The goal is to achieve high prediction accuracy and low MSE, surpassing simple linear models in forecast accuracy and classification.

