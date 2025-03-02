# Energy Consumption Prediction using CNN-LSTM

This repository contains Jupyter notebooks demonstrating a deep learning approach for predicting power consumption using combined energy and temperature data. The project showcases a CNN-LSTM model that processes time-series data through feature engineering, sequence creation, and model training, and includes examples for evaluating and visualizing predictions on a daily, weekly, and monthly basis.

## Repository Link

[Predictive_Model_LSTM](https://github.com/ismayilmehili/Predictive_Model_LSTM.git)

## Project Overview

- **Data Preprocessing & Feature Engineering:**  
  Loads the `Combined_Energy_and_Temperature_Data.csv` dataset, converts timestamps, and creates additional features (Hour, DayOfWeek, Month).

- **Model Building & Training:**  
  Implements a CNN-LSTM model with dropout regularization to predict power consumption. The model is trained with a sequence-based approach and evaluated using RMSE, MAE, and MAPE metrics.

- **Visualization & Evaluation:**  
  Includes functions to plot learning curves as well as daily, weekly, and monthly prediction comparisons between actual and predicted power consumption.

- **Model Persistence & Inference:**  
  Demonstrates saving/loading of the trained model and scaler, and provides examples for making predictions in a new environment, including integration with Google Colab for mounting Google Drive.

## Repository Structure

- **Notebook 1:**  
  Model training and evaluation with data preprocessing, feature engineering, sequence creation, and prediction plotting.
- **Notebook 2:**  
  Extension of Notebook 1 with added functionality for saving and loading the trained model and scaler.
- **Notebook 3:**  
  Model inference using the persisted model, including examples for daily, weekly, and monthly prediction plots and Google Colab integration.

## Requirements

- Python 3.8+
- TensorFlow & Keras
- Pandas
- NumPy
- scikit-learn
- Matplotlib
- joblib

## How to Use

1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/ismayilmehili/Predictive_Model_LSTM.git
