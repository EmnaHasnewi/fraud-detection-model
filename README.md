# Fraud Detection Model

This repository contains a machine learning model for detecting fraudulent credit card transactions using a **Logistic Regression** classifier. The model is trained on the publicly available **Credit Card Fraud Detection dataset** from Kaggle. The dataset contains transactions made by credit cards, and the goal is to predict whether a given transaction is fraudulent (Class = 1) or not (Class = 0).

## Project Overview

- **Problem**: Fraudulent credit card transactions detection.
- **Techniques Used**:
  - **Logistic Regression** for classification.
  - **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset and improve prediction accuracy for the minority class (fraudulent transactions).
  - **StandardScaler** for feature scaling.
  
## Installation

### Prerequisites

To run this project, you need the following libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `imblearn`
- `matplotlib`
- `seaborn`
- `joblib`

You can install them via pip:

```bash
pip install pandas numpy scikit-learn imblearn matplotlib seaborn joblib
