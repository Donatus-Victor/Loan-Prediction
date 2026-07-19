# Loan Eligibility & Credit Risk Model

A machine learning classification model that predicts loan eligibility and credit risk, built to support automated lending decisions.

## Overview
This project uses historical applicant and financial data to classify borrowers by credit risk and eligibility status, helping simulate the kind of decision support used in digital lending pipelines.

## Features
- Data cleaning and feature engineering on applicant/financial records
- Classification model to predict credit risk and loan eligibility
- Model evaluation using standard classification metrics (accuracy, precision, recall, ROC-AUC)
- Reproducible training pipeline

## Tech Stack
- **Language:** Python
- **Libraries:** Scikit-learn, Pandas, NumPy
- **Model type:** Classification (e.g., Logistic Regression / Random Forest / XGBoost)

## How It Works
1. Load and preprocess applicant data (handle missing values, encode categorical features)
2. Engineer features relevant to creditworthiness
3. Train and validate the classification model
4. Evaluate performance and interpret key risk drivers

## Getting Started
```bash
git clone https://github.com/Donatus-Victor/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt
python app.py
```

## Results
Model performance metrics and key findings are documented in the notebook/report included in this repo.

## Author
**Donatus Victor** — Senior Data Scientist
[LinkedIn](https://linkedin.com/in/donatusvictor) | [GitHub](https://github.com/Donatus-Victor)
