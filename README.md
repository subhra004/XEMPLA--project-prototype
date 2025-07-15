# Xempla Smart Asset Monitoring Prototype

A simple end-to-end machine learning prototype for *predictive maintenance, **fault detection, and **energy optimization* for industrial facilities — inspired by Xempla’s Decision Intelligence platform.

---

## Smart Asset Monitoring using Machine Learning

This project shows how ML can help monitor asset health using simple anomaly detection, condition-based maintenance, and energy usage prediction — all on time-series sensor data.

---

## Features

- *Fault Detection:*  
  Isolation Forest detects anomalies in vibration & temperature sensor data.

- *Condition-Based Maintenance (CBM):*  
  A rolling health score is calculated from normalized vibration levels.

- *Energy Usage Prediction:*  
  Linear Regression predicts energy usage trends from operating data.

---

## Technologies Used

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Isolation Forest
- Linear Regression

---

##  Workflow Overview

1️⃣ *Data Preparation*
- Synthetic time-series data (temperature, vibration, energy).
- Some data points contain injected anomalies.

2️⃣ *Fault Detection*
- Isolation Forest flags unusual behavior.

3️⃣ *Condition-Based Maintenance*
- A health score is computed and smoothed to simulate asset degradation.

4️⃣ *Energy Prediction*
- Simple regression model forecasts energy usage.

---

## ✅ Results

- ✅ Anomalies clearly flagged in plots.
- ✅ Health score trend visible for maintenance planning.
- ✅ Predicted vs actual energy usage plotted for comparison.

---


