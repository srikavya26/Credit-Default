## Credit Default 
****This project analyzes a credit card client dataset to predict the likelihood of default in the next payment cycle. It includes exploratory data analysis, preprocessing, feature scaling, imbalance techniques, and model training. Multiple algorithms such as Decision Trees, XGBoost, and ANN are evaluated. The goal is to build an accurate and interpretable credit default prediction system.****
#### Dataset : 
*****1.https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients***** 
# Credit Default Prediction - Machine Learning Analysis

![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-complete-success)
![ML](https://img.shields.io/badge/machine-learning-orange)
![Finance](https://img.shields.io/badge/domain-finance-lightgrey)

## 📊 Project Overview

A comprehensive machine learning analysis for predicting credit card defaults using the UCI Default of Credit Card Clients dataset. This project implements and compares 7 different machine learning algorithms with extensive feature engineering and visualization.

### 🎯 Key Features
- **7 ML Models**: Neural Network, Gradient Boosting, XGBoost, Random Forest, Decision Tree, Logistic Regression, Naive Bayes
- **Complete Pipeline**: Data loading → preprocessing → EDA → feature engineering → modeling → evaluation
- **Advanced Visualization**: Interactive plots for model comparison and analysis
- **Feature Engineering**: Created 15+ domain-specific features
- **Class Imbalance Handling**: SMOTE implementation for better model training

## 📈 Performance Summary

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|----------|-----------|--------|----------|---------|
| Neural Network | 0.6728 | 0.3753 | 0.7212 | 0.4937 | **0.7675** |
| Gradient Boosting | **0.8037** | 0.5678 | 0.4702 | **0.5144** | 0.7664 |
| XGBoost | 0.6800 | 0.3784 | 0.6956 | 0.4902 | 0.7578 |
| Random Forest | 0.7975 | 0.5514 | 0.4529 | 0.4973 | 0.7517 |
| Decision Tree | 0.7825 | 0.5087 | 0.4868 | 0.4975 | 0.7455 |
| Logistic Regression | 0.6775 | 0.3661 | 0.6262 | 0.4621 | 0.7182 |
| Naive Bayes | 0.3250 | 0.2388 | 0.9382 | 0.3807 | 0.7106 |

**Best Model**: Neural Network (Highest ROC-AUC: 0.7675)

## 🚀 Quick Start

### Prerequisites
- Python 3.9+
- pip package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/srikavya26/Credit-Default.git
cd credit-default-prediction

# Run the complete analysis pipeline
python credit_default_analysis.py

# Or import and run from Python
from main import run_complete_analysis
run_complete_analysis()
