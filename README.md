# 📈 Groundwater potability

Welcome to this project where we explore **stock price prediction** using **CatBoost**, a powerful gradient boosting library, and compare its performance on **CPU vs GPU**. This repository is designed for data scientists, ML engineers, and finance enthusiasts who are interested in the practical applications of ML in stock forecasting and hardware performance evaluation.

---

## 📚 Table of Contents

- [🔍 Overview](#-overview)
- [🚀 Objective](#-objective)
- [📦 Features](#-features)
- [🧠 Algorithms Used](#-algorithms-used)
- [⚙️ Setup & Installation](#️-setup--installation)
- [📊 Dataset](#-dataset)
- [🔧 Methodology](#-methodology)
- [⚡ GPU vs. CPU Benchmark](#-gpu-vs-cpu-benchmark)
- [📈 Evaluation Metrics](#-evaluation-metrics)
- [📌 Results](#-results)
- [📁 Project Structure](#-project-structure)
- [🛠️ Technologies Used](#️-technologies-used)
- [📎 References](#-references)
- [🙌 Acknowledgements](#-acknowledgements)
- [📬 Contact](#-contact)

---

## 🔍 Overview

This project aims to:
- Predict stock price movement using machine learning.
- Analyze and visualize the impact of hardware acceleration on model training.
- Compare runtime performance between CPU and GPU.
- Evaluate the model using industry-standard classification metrics.

---

## 🚀 Objective

- To build a predictive model using `CatBoost` to classify future stock price movement.
- To perform a benchmark analysis comparing training time and accuracy on CPU vs GPU.
- To interpret and visualize model performance using ROC-AUC, accuracy, and other metrics.

---

## 📦 Features

- ✅ Data Preprocessing & Feature Engineering  
- ✅ Stock Price Prediction using `CatBoostClassifier`  
- ✅ Support for both CPU and GPU modes  
- ✅ Confusion Matrix & Classification Report  
- ✅ ROC-AUC Score Visualization  
- ✅ Performance Benchmarking  

---

## 🧠 Algorithms Used

- **CatBoostClassifier**: A gradient boosting algorithm developed by Yandex, especially effective with categorical features and robust to overfitting.
- **Grid Search (Optional)**: For hyperparameter tuning.
- **ROC-AUC** and **Accuracy** for model evaluation.

---

## ⚙️ Setup & Installation

Make sure Python 3.7+ is installed.

```bash
# Clone the repository
git clone https://github.com/yourusername/stock-catboost-gpu-cpu.git
cd stock-catboost-gpu-cpu

# Create virtual environment (optional)
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
