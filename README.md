# Stress & Sleep Pattern Analysis using Wearable Sensor Data

##  Project Status

This project is currently **ongoing**.
Core data analysis and preprocessing have been completed, and machine learning models for stress prediction are under development.

---

##  Overview

This project focuses on analyzing physiological data collected from wrist-based wearable devices to detect **stress levels** and evaluate **sleep patterns** using data mining and machine learning techniques.

With the increasing use of wearable technology, this project aims to build a **data-driven framework** for continuous, non-intrusive monitoring of stress and sleep behavior.

---

##  Objectives

* Analyze physiological signals such as heart rate, HRV, and activity data
* Perform preprocessing and feature extraction on raw sensor data
* Study sleep patterns including duration and quality
* Predict stress levels (low, medium, high) using machine learning
* Identify relationships between sleep behavior and stress
* Evaluate model performance using standard metrics

---

##  Dataset

This project uses publicly available wearable datasets:

* **WESAD (Wearable Stress and Affect Detection Dataset)**
* **MMASH (Multilevel Monitoring of Activity and Sleep in Healthy People)**

Note:
Datasets are not included in this repository due to size constraints.
They can be accessed from their respective public sources.

---

##  Technologies Used

* **Python**
* **Pandas, NumPy** (Data Processing)
* **Matplotlib, Seaborn** (Visualization)
* **Scikit-learn** (Machine Learning)

---

##  Methodology

### 1. Data Preprocessing

* Handling missing values
* Noise removal and normalization
* Segmentation of time-series data

### 2. Feature Extraction

* Statistical features (mean, variance, std deviation)
* Physiological features (HRV, activity levels)
* Sleep-related features

### 3. Exploratory Data Analysis (EDA)

* Visualization of stress and sleep trends
* Correlation analysis between variables

### 4. Machine Learning (Ongoing)

* Models being explored:

  * Support Vector Machine (SVM)
  * Random Forest
  * K-Nearest Neighbors (KNN)
* Evaluation metrics:

  * Accuracy
  * Precision, Recall
  * F1-Score

---

## 📂 Project Structure

```
Stress-Sleep-Analysis/
│
├── dataset/                 # (ignored in GitHub)
├── stress_sleep_analysis.ipynb
├── README.md
└── .gitignore
```

---

##  Current Progress

* ✅ Data loading and preprocessing completed
* ✅ Exploratory Data Analysis performed
* 🔄 Feature engineering in progress
* 🔄 Machine learning models under implementation

---

##  Future Work

* Implement and compare multiple ML models
* Improve feature engineering for better accuracy
* Build a predictive system for real-time stress detection
* Extend project towards healthcare applications

---

##  Key Insight

This project explores how **sleep patterns directly influence stress levels**, contributing toward better understanding of lifestyle-driven health issues.





This project is part of ongoing work in **data mining and machine learning** and will be continuously improved with additional models and insights.
