# IoT Data Pipeline: Air Quality Prediction

This project implements an end-to-end IoT data pipeline as part of the Advanced Computer Programming course. It covers everything from data acquisition and cleaning to model deployment using ONNX.

## Project Overview
The goal is to predict Air Quality (specifically Benzene concentration) based on various sensor readings using the UCI Air Quality dataset.

### Key Features:
- [cite_start]**Data Acquisition**: Loading real-world sensor data from UCI Repository[cite: 33, 34].
- [cite_start]**Preprocessing**: Handling missing values (marked as -200), removing noise, and feature scaling[cite: 43, 44].
- [cite_start]**Model Training**: Training a Linear Regression model using Scikit-Learn[cite: 51, 53].
- [cite_start]**ONNX Export**: Converting the trained model to ONNX format for cross-platform inference[cite: 52, 56].
- [cite_start]**Inference**: Loading and running the model using `onnxruntime`[cite: 59, 61].
- [cite_start]**Visualization**: Plotting actual vs. predicted values for performance evaluation[cite: 67, 68].

## Deliverables
- `main.py`: The complete Python pipeline.
- [cite_start]`air_quality_model.onnx`: The exported model[cite: 73].
- [cite_start]`AirQualityUCI.csv`: The dataset used[cite: 72].
- [cite_start]`performance_plot.png`: Model evaluation chart[cite: 75].

## How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn skl2onnx onnxruntime matplotlib