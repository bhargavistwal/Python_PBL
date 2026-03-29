# WiFi Congestion Analysis using Machine Learning

## Overview
This project analyzes and predicts WiFi congestion levels using machine learning techniques.  
It follows a complete pipeline from data generation to prediction.

## Project Phases

### 1. Data Collection & EDA
- Generated synthetic dataset using NumPy
- Performed exploratory data analysis (EDA)
- Removed outliers using IQR
- Saved cleaned dataset

### 2. Data Preprocessing
- Loaded cleaned dataset
- Handled encoding of categorical values
- Applied feature scaling (MinMaxScaler)
- Split data into training and testing sets

### 3. Model Training
- Trained Logistic Regression model
- Improved dataset by using multiple features
- Ensured balanced and realistic learning

### 4. Model Evaluation
- Evaluated model using:
  - Accuracy
  - Confusion Matrix
  - Precision, Recall, F1-score
- Analyzed model performance

### 5. Model Prediction
- Implemented manual prediction system
- Allowed custom input testing
- Predicted congestion level (Low, Medium, High)

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Seaborn

## Conclusion
The project successfully demonstrates a complete machine learning workflow for predicting WiFi congestion using multiple features.
