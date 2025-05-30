# 🛺 Uber Ride Price Prediction

This project predicts the fare price of Uber rides based on ride details such as pickup and dropoff locations, time, and number of passengers. The project is implemented in a Jupyter Notebook using Python and several machine learning libraries.

---

## 📌 Project Overview

Uber ride fares can vary due to several factors including distance, passenger count, and traffic patterns. In this project, we:
- Load and explore a real-world Uber ride dataset
- Clean and preprocess the data
- Engineer useful features such as distance
- Visualize important trends
- Train regression models to predict ride fares
- Evaluate model performance

---

## 📂 Dataset

The dataset used contains historical Uber ride data, including:
- Pickup and dropoff datetime
- Pickup and dropoff latitude & longitude
- Passenger count
- Fare amount

> **Dataset Source**: uber.csv

---

## 🚀 Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas** and **NumPy** for data manipulation
- **Matplotlib** and **Seaborn** for visualization
- **XGBoost**  for boosted decision tree models
- **Haversine formula** for distance calculation

---

## 🧠 Models Applied
- XGBoost Regressor 

Model performance is evaluated using:
- RMSE (Root Mean Squared Error)
- R² Score

---

## 📊 Results

- The model achieved an R² score of `99.92`
- RMSE was `0.017` indicating reasonable prediction error

---
