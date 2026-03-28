# Phase 3: Model Training

## Overview
In this phase, a machine learning model was trained to predict WiFi congestion levels.

## Model Used
- Logistic Regression

## Steps Performed
- Loaded preprocessed dataset
- Encoded target variable
- Balanced dataset to avoid class imbalance
- Applied feature scaling
- Split data into training and testing sets
- Trained Logistic Regression model
- Made predictions on test data

## Model Improvement
Initially, the dataset was imbalanced, causing biased predictions.
To fix this, dataset balancing was applied using sampling techniques.
This improved prediction for all classes (Low, Medium, High).
