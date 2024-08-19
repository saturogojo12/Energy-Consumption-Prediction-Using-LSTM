# Energy Consumption Prediction using LSTM

## Project Overview

This project involves predicting energy consumption using historical data and an LSTM (Long Short-Term Memory) model. The dataset used contains hourly energy consumption data from 2004 to 2018.

## Dataset

- **Source**: AEP Hourly Energy Consumption Data
- **Features**:
  - `Datetime`: Timestamp of the observation
  - `AEP_MW`: Energy consumption in megawatts (MW)

## Data Preprocessing

- **Datetime Features**:
  - Extracted `Month`, `Year`, `Date`, `Time`, `Week`, and `Day` from `Datetime`.
- **Resampling**:
  - Data was resampled to daily averages for model input.

## Model Architecture

- **Layers**:
  1. Four LSTM layers with 50 units each, followed by Dropout regularization (0.2).
  2. Output layer with 1 unit to predict energy consumption.

- **Optimizer**: Adam
- **Loss Function**: Mean Squared Error

## Training

- **Training Data**: 4995 samples
- **Test Data**: 100 samples
- **Batch Size**: 32
- **Epochs**: 20

## Results

- The model was trained over 20 epochs with a decreasing loss value across epochs, indicating improved prediction accuracy.

## Visualizations

1. **Yearly Energy Consumption**: Line plot showing energy consumption trends over the years.
2. **Energy Distribution**: Distribution of energy consumption values.
3. **Energy vs Time**: Relationship between energy consumption and time of day.

## Conclusion

The LSTM model successfully predicts energy consumption based on historical data, showing promising results for forecasting future energy demands.
