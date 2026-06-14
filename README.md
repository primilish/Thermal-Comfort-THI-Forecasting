# Thermal Comfort Forecasting

## Overview

This project investigates Thermal Humidity Index (THI) forecasting using deep learning models (LSTM and GRU) based on environmental sensor data collected from multiple monitoring nodes.

The study evaluates forecasting performance across different sensor locations and prediction horizons to identify the most reliable approach for thermal comfort prediction.

## Sensor Nodes

The forecasting models were developed and evaluated using data from:

- ESP Indoor
- ESP Outdoor
- Raspberry Pi Indoor
- Raspberry Pi Outdoor

## Objectives

- Forecast future THI values using historical environmental data
- Compare LSTM and GRU performance
- Evaluate model performance across multiple sensor locations
- Analyze forecasting horizons of 10, 30, and 60 minutes

## Methodology

1. Data preprocessing and quality control
2. THI calculation and feature preparation
3. LSTM model training
4. GRU model training
5. Performance evaluation using multiple metrics
6. Comparative analysis across sensor nodes

## Evaluation Metrics

- RMSE (Root Mean Square Error)
- MAPE (Mean Absolute Percentage Error)
- R² Score

## Technologies Used

- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Repository Structure

```text
├── esp_indoor/
├── esp_outdoor/
├── raspberry_indoor/
├── raspberry_outdoor/
├── analysis/
│   └── analisis_hasil.ipynb
├── README.md
└── .gitignore
```

## Results

Performance comparison and visualization are available in:

```text
analysis/analisis_hasil.ipynb
```

The notebook contains:
- Actual vs predicted THI visualization
- LSTM vs GRU comparison
- RMSE, MAPE, and R² evaluation
- Forecast horizon analysis (10, 30, and 60 minutes)

## Note

This project was developed during an internship project. Certain datasets may not be publicly distributed.

## Author

Annisa Primahapsari
