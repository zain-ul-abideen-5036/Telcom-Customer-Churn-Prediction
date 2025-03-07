# Telcom-Customer-Churn-Prediction

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-brightgreen)

A machine learning project to predict customer churn using telco customer data.
---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Key Results](#key-results)
- [Model Evaluation](#model-evaluation)
- [Repository Structure](#repository-structure)
---

## Project Overview
This project analyzes customer churn patterns in telecommunications data using machine learning techniques. The workflow includes:

- Data preprocessing and cleaning
- Exploratory data analysis
- Feature engineering
- Model training (Decision Tree and Random Forest classifiers)
- Model evaluation and comparison
- Feature importance analysis
---

## Dataset
The dataset used is the [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn), containing information about:
- Customer demographics
- Services subscribed
- Account information
- Churn status (target variable)
---

## Installation
1. Clone repository:
```bash
git clone https://github.com/zain-ul-abideen-5036/Telcom-Customer-Churn-Prediction.git
```
2. Install requirements:
```bash
pip install -r requirements.txt
```

**Required libraries:**
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
---

## Usage
1. Open TelcoCustomerChurn.ipynb in Jupyter Notebook
2. Run cells sequentially to:
  - Preprocess data
  - Train machine learning models
  - Evaluate model performance
  - Generate visualizations
---

## Key Results
- Random Forest achieved 80% accuracy
- Decision Tree achieved 77% accuracy
- Key churn indicators: tenure, monthly charges, and contract type
---

## Model Evaluation
**Performance Metrics**

| Model |	Accuracy	| Precision	| Recall | F1 Score |
|-------|-----------|-----------|--------|----------|
| **Random Forest** |	0.80 |	0.70 |	0.45 | 0.55 |
| **Decision Tree**	| 0.77 |	0.58 |	0.48 | 0.53 |
---

## Repository Structure
```
telco-customer-churn-prediction/
│ WA_Fn-UseC_-Telco-Customer-Churn.csv
│ TelcoCustomerChurn.ipynb
├── README.md
└── requirements.txt
```
---
