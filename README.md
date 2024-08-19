Project Description
This project involves the prediction of energy consumption using an LSTM (Long Short-Term Memory) neural network model. The dataset used is hourly energy consumption data from AEP (American Electric Power) spanning from 2004 to 2018. The project aims to analyze the time series data, perform data preprocessing, and build a predictive model to forecast future energy consumption.

README
Overview
This repository contains the code and data for predicting energy consumption using an LSTM neural network model. The project is implemented in Python and uses libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Keras.

Features
Data Loading and Preprocessing:

Load and explore the AEP hourly energy consumption dataset.
Perform data cleaning, including handling missing values and extracting relevant date-time features.
Data Visualization:

Visualize energy consumption trends over the years.
Explore energy distribution patterns and energy consumption concerning time (monthly analysis).
Model Building:

Develop an LSTM model with multiple layers and dropout regularization.
Train the model on the preprocessed data to predict future energy consumption.
Evaluation:

Evaluate the model's performance by analyzing the loss over epochs.
Requirements
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Keras
Installation
Clone the repository and install the necessary packages:

bash
Copy code
git clone https://github.com/yourusername/energy-consumption-prediction.git
cd energy-consumption-prediction
pip install -r requirements.txt
Usage
Load Data:
Load the dataset and perform initial data exploration.

Preprocessing:
Extract date-time features and resample the data for better analysis.

Model Training:
Build and train the LSTM model on the processed data.

Prediction:
Use the trained model to predict future energy consumption.

Visualization:
Visualize the model's predictions and analyze the results.

Files
AEP_hourly.csv: The dataset containing hourly energy consumption data.
energy_consumption_prediction.ipynb: Jupyter Notebook with the full code implementation.
requirements.txt: List of required Python packages.
