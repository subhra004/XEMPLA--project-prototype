# XEMPLA--project-prototype
Xempla project prototype- An end-to-end deep learning pipeline for predictive maintenance via vibration signal classification, enabling intelligent monitoring of industrial machinery

## Smart Asset Monitoring using Deep Learning & Vibration Analysis
This project presents an end-to-end deep learning pipeline for predictive maintenance via vibration signal classification, enabling intelligent monitoring of industrial machinery. By analyzing vibration patterns, the model can detect and classify machinery health conditions using signal processing and a CNN-based deep learning model.

## Features

 Fault detection and classification of rotating machinery (bearings).

 Signal preprocessing using Fast Fourier Transform (FFT).

 1D Convolutional Neural Network for spectral feature extraction.

 High-accuracy classification of healthy and faulty conditions.

 Designed for time-series vibration data from accelerometer sensors.



##  Technologies Used
Python 3.x

NumPy, Pandas

Matplotlib, Seaborn

Scikit-learn

TensorFlow / Keras

Signal Processing: FFT


## Workflow Overview
1. Data Preparation

   Vibration signals are collected from different machinery conditions.
   Data is labeled based on condition (e.g., healthy, outer fault, inner fault).
   Signals are converted into frequency domain using FFT.
   
2. Model Development
   
   A 1D CNN is used for classification of FFT-processed signals.
   Model architecture includes multiple convolutional and dense layers.
   Trained and validated on labeled dataset.

3. Evaluation

    Accuracy, loss, and classification report are generated.
    Confusion matrix visualized to assess model performance.

## Results
✅ Achieved high classification accuracy across different fault types.

🔍 Clear distinction between healthy and faulty signals via FFT visualization.

🧠 CNN model effectively learns features from spectral domain.



