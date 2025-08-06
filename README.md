# WaterQual-HybridML

Improving prediction of water quality indices using novel hybrid machine-learning algorithms.

---

## Overview

This repository contains a Python pipeline designed to enhance the prediction accuracy of Water Quality Indices (WQI) by leveraging novel hybrid machine-learning algorithms. The approach integrates ensemble and hybrid models such as Random Forest with Bagging, Decision Tree with Bagging, and Gradient Boosting to improve robustness and predictive performance.

---

## Key Features

- **Data Loading:** Load cleaned water quality data (`cleaned_data.csv`)
- **Preprocessing:** Train-test split and feature standardization
- **Models:**
  - Random Forest (RF)
  - Random Forest + Bagging (Hybrid)
  - Decision Tree + Bagging (Hybrid)
  - Gradient Boosting (Hybrid approach)
- **Evaluation Metrics:**
  - R² (Coefficient of Determination)
  - RMSE (Root Mean Square Error)
  - MAE (Mean Absolute Error)
  - NSE (Nash–Sutcliffe Efficiency)
  - PBIAS (Percent Bias)

---

## Setup & Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/WaterQual-HybridML.git
   cd WaterQual-HybridML
