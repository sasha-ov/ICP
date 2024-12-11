# Human Activity Recognition (HAR) Using Deep Learning Models

This project focuses on evaluating various neural network architectures for the Human Activity Recognition (HAR) dataset using smartphones. The primary goal is to determine which model performs best at recognizing static activities such as **Sitting**, **Standing**, and **Laying**.

1. **Convolutional Neural Network (CNN)**
2. **Long Short-Term Memory Network (LSTM)**
3. **Hybrid CNN-LSTM**
4. **Temporal Convolutional Network (TCN)**

The goal is to classify activities such as walking, sitting, standing, and more, based on sensor data collected from smartphones.

---

## Table of Contents

- [Dataset Overview](#dataset-overview)
- [Project Details](#project-details)
- [Architectures](#architectures)
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

1. Implement and train four different neural network architectures.
2. Compare the performance of each model, specifically on static activities (**Sitting**, **Standing**, and **Laying**).
3. Visualize and analyze the results to determine the most effective approach.


---

## Architectures

### 1. Convolutional Neural Network (CNN)
A CNN is used to extract spatial features from the sensor data. The architecture includes multiple convolutional and pooling layers.

**Architecture Diagram:**

![CNN Architecture](images/cnn_architecture.png)

### 2. Long Short-Term Memory (LSTM)
LSTMs are used to model temporal dependencies in the data. The architecture includes LSTM layers followed by dense layers.

**Architecture Diagram:**

![LSTM Architecture](images/lstm_architecture.png)

### 3. Hybrid CNN-LSTM
The hybrid model combines CNN layers for feature extraction and LSTM layers for temporal modeling.

**Architecture Diagram:**

![CNN-LSTM Architecture](images/cnn_lstm_architecture.png)

### 4. Temporal Convolutional Network (TCN)
TCNs leverage causal convolutions to capture temporal patterns in the data efficiently.

**Architecture Diagram:**

![TCN Architecture](images/tcn_architecture.png)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/HAR-DeepLearning.git

