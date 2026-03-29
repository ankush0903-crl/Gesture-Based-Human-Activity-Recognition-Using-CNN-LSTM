# Gesture-Based-Human-Activity-Recognition-Using-CNN-LSTM
Developed a human activity recognition system using a CNN-LSTM model on wearable sensor data. Classified activities like walking, running, sitting, and standing using accelerometer and gyroscope signals. Achieved around 70% accuracy through effective preprocessing and sequence modeling.

 Overview
This project focuses on human activity recognition (HAR) using wearable sensor data and deep learning techniques. A hybrid CNN-LSTM model is used to analyze accelerometer and gyroscope signals to classify activities like walking, running, sitting, and standing. The system demonstrates effective learning of both spatial and temporal motion patterns.

Features
1.Classifies multiple human activities
2.Uses CNN for feature extraction
3.Uses LSTM for sequence learning
4.Handles real-world sensor data
5.Achieves ~70% accuracy

Model Architecture
1.CNN (Conv1D): Extracts spatial features
2.MaxPooling: Reduces dimensions
3.LSTM: Captures temporal patterns
4.Dense Layer: Final classification

Technologies Used
1.Python
2.TensorFlow / Keras
3.NumPy
4.Matplotlib

Dataset
1.UCI Human Activity Recognition Dataset
2.Includes accelerometer and gyroscope data

Results
1.Training Accuracy: ~77%
2.Validation Accuracy: ~70%
3.Test Accuracy: ~67–72%
