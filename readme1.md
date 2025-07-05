# Credit Card Fraud Detection System

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

An end-to-end machine learning system for detecting fraudulent credit card transactions with 91% recall.

## Features
- Advanced handling of class imbalance (SMOTE + class weighting)
- Threshold optimization for business needs
- Multiple model comparison (XGBoost, Random Forest, Logistic Regression)
- Anomaly detection integration

## Quick Start
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection

# Install dependencies
pip install -r models/requirements.txt

# Run Jupyter notebook
jupyter notebook notebooks/Fraud_Detection_System.ipynb
