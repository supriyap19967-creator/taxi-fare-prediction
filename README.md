# Taxi Fare Prediction – End-to-End Machine Learning Project

## Overview
This project demonstrates an end-to-end machine learning workflow to predict taxi fares using trip-related features. The goal is to build, train, evaluate, and export a production-ready ML model using TensorFlow and Keras.

This project aligns with **Course 2: Build, Train, and Deploy ML Models with Keras (Google Cloud learning path)**.

---

## Problem Statement
Predict the taxi fare amount based on trip details such as pickup and drop-off coordinates and passenger count.

---

## Dataset
- Source: Kaggle – NYC Taxi Fare Prediction
- File used: `train.csv`
- Target variable: `fare`

---

## Machine Learning Workflow
1. Data loading and inspection
2. Basic data cleaning (null removal, invalid fare filtering)
3. Feature-target separation
4. Train–test split
5. Model building using Keras
6. Model training and evaluation
7. Model export for future deployment

---

## Model Architecture
- Input layer (numeric features)
- Dense layer (ReLU)
- Dense layer (ReLU)
- Output layer (Regression)

Loss function:
- Mean Squared Error (MSE)

Evaluation metric:
- Mean Absolute Error (MAE)

---

## Results
- Model trained successfully
- MAE achieved on test data
- Model exported in `.keras` format for reuse and deployment

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

## Project Status
The model has been trained and saved locally.


---

## Key Learnings
- End-to-end ML workflow with Keras
- Model evaluation for regression problems
- Exporting trained models in production-ready format
- Preparing ML projects for cloud deployment

---

## Author
Supriya
