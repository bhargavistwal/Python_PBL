# Phase 5: Model Prediction

## Overview
In this phase, the trained machine learning model is used to predict WiFi congestion levels based on new input data.

## Objective
To demonstrate how the model can be used in real-world scenarios by providing custom input and obtaining predictions.

## Steps Performed
- Loaded the cleaned dataset
- Applied preprocessing (encoding and scaling)
- Trained Logistic Regression model
- Provided manual input data
- Applied same scaling to input data
- Used trained model to predict congestion level

## Input Features
The model takes the following features as input:
- num_devices
- latency
- packet_loss
- signal_strength
- bandwidth
- channel
- noise_level
- throughput
- upload_speed
- download_speed
- jitter
- distance
- obstacles
- router_load

## Output
The model predicts one of the following congestion levels:
- Low
- Medium
- High

## Example
Sample input data is provided in the code, which can be modified to test different scenarios.

## Conclusion
This phase demonstrates the practical usability of the model by allowing predictions on new data, completing the machine learning pipeline.
