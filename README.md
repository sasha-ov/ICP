# Human Activity Recognition (HAR) Using Deep Learning Models

This project implements Human Activity Recognition (HAR) using the UCI dataset and explores the performance of various deep learning models, including:

- **Convolutional Neural Network (CNN)**
- **Long Short-Term Memory Network (LSTM)**
- **CNN-LSTM Hybrid**
- **Temporal Convolutional Network (TCN)**

The goal is to classify activities such as walking, sitting, standing, and more, based on sensor data collected from smartphones.

---

## Table of Contents

- [Dataset Overview](#dataset-overview)
- [Project Details](#project-details)
- [Models Implemented](#models-implemented)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## Dataset Overview

The dataset used in this project is the **UCI Human Activity Recognition Using Smartphones** dataset, which can be downloaded [here](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones).

### Key Features:
- **Activities**: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING.
- **Subjects**: Data collected from 30 participants wearing smartphones at their waist.
- **Sensors**: Accelerometer and gyroscope signals preprocessed with noise filters.
- **Data Windows**: Sliding windows of 2.56 seconds (128 readings/window) with 50% overlap.
- **Preprocessing**: Butterworth low-pass filter to separate body motion and gravity components.

---

## Project Details

This project evaluates different deep learning architectures for HAR to identify the best-performing model in terms of accuracy, training time, and robustness.

---

## Models Implemented

1. **Convolutional Neural Network (CNN)**
   - Extracts spatial features from sensor data.

2. **Long Short-Term Memory Network (LSTM)**
   - Captures temporal dependencies in the time-series data.

3. **CNN-LSTM Hybrid**
   - Combines CNN for feature extraction and LSTM for sequence modeling.

4. **Temporal Convolutional Network (TCN)**
   - Explores temporal patterns using a fully convolutional structure.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/HAR-DeepLearning.git

