# Machine Learning-Based Intrusion Detection and Response for SSH & FTP Brute Force Attacks

A Machine Learning-based Intrusion Detection System (IDS) designed to detect **SSH and FTP brute force attacks** using the **CSE-CIC-IDS-2018 dataset**.

---

## Project Overview

This project focuses on building an efficient Network Intrusion Detection System (NIDS) capable of identifying brute force attacks by leveraging machine learning models.

Key highlights:
- Dataset: CIC-IDS-2018 (Brute Force subset)
- Attacks covered: SSH & FTP brute force
- Algorithms used:
  - Decision Tree (DT)
  - Random Forest (RF)
  - K-Nearest Neighbors (KNN)
  - Naïve Bayes
  - Multi-Layer Perceptron (MLP)

---

## Key Contributions

- Large-scale dataset analysis for malicious traffic detection  
- Feature selection using Random Forest importance  
- Performance optimization (CPU time & model size)  
- High accuracy detection models for real-time IDS  

---

## System Architecture

![Architecture](Media/Architecture-Final.jpg)

---

## Model Performance

![Performance](Media/PerformanceAnalysis.png)

- Decision Tree & Random Forest achieved the best results:
  - High Accuracy
  - Strong Precision & Recall
  - Fast Training & Prediction

---

## Training & Prediction

### Training Phase
![Training](Media/Training.jpg)

### Prediction Output
![Prediction](Media/Prediction.jpg)

---

## Packet Collection Demo

<video src="media/videos/CollectingPackets.mp4" controls width="600"></video>

---

