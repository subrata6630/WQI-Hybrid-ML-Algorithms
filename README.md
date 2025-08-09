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
 
    
- **Grape:**
   - PBIAS (Percent Bias)
   - Heavy metals detected: Lead (Pb), Cadmium (Cd), Arsenic (As), and Mercury (Hg) were measured in grape samples.
   - Lead levels: Recorded at 0.034–0.073 mg/kg, which in some cases exceeded permissible limits set by food safety guidelines.
   - Cadmium levels: Found at 0.005–0.012 mg/kg, generally within safe limits.
   - Arsenic and Mercury: Detected in trace amounts, below maximum allowable concentrations.
   - Health risk: Calculated Target Hazard Quotient (THQ) for Pb was significant in some samples, indicating potential chronic health risks with long-term consumption.
 
- **Fig:**
   - Heavy metals detected: Similar to grapes — Pb, Cd, As, and Hg were tested.
   - Lead levels: Ranged between 0.028–0.060 mg/kg, mostly under permissible limits.
   - Cadmium levels: 0.004–0.010 mg/kg, well within safe levels.
   - Arsenic and Mercury: Present only in very small quantities, far below dangerous thresholds.
   - Health risk: THQ values were lower than grapes, suggesting relatively less risk, but still monitored for Pb due to bioaccumulation concerns.

---

## Setup & Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/WaterQual-HybridML.git
   cd WaterQual-HybridML
