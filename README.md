# 🔧 Predictive Maintenance: Failure Classification

This project demonstrates predictive maintenance by classifying machine failures  

The project leverages a synthetic dataset designed to mimic real-world predictive maintenance scenarios.

---

Google Colab Link

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nce52pTxcI4u7oafOz3VoJEserRPFQCp?usp=sharing)


---

## 🌟 Introduction
Predictive maintenance is a proactive approach that utilizes data analysis to predict when equipment failure might occur. By anticipating failures, timely maintenance can be performed, reducing downtime and saving costs.

---

## 📊 Dataset Overview
The synthetic dataset simulates real-world maintenance scenarios with:
- **10,000 records** and **14 features**
- **Target variable**:
  - `Failure_Type`: Specifies the type of failure (multiclass labels).
- **Features** include:
  - Continuous: Temperature, rotational speed, torque, tool wear, etc.
  - Categorical: Product quality, serial numbers, etc.

---

## 🚀 Project Workflow
1. **EDA & Data Preperations**:
   - Statistical Analysis
   - Visualizations
   - Handling missing values and outliers
   - Skewness Analysis
   - Correlation Analysis

2. **Feature Engineering & Normalization**:
   - Three new features were engineered
   - Ordinal and Standard normalization 

3. **Model Training**:
   - Multiclass classification using algorithms like Decision Trees, Gradient Boosting, etc.

4. **Evaluation**:
   - Metrics: Accuracy, Precision, Recall, F1-Score, Support
   - Classification report

---

## 🛠️ Requirements
- Python 3.8 or above
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
