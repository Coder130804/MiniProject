# Explainable AI for Myocardial Infarction
## Overview
This project applies machine learning techniques to predict the likelihood of myocardial infarction using clinical data. It focuses on both model performance and interpretability. The primary objective is to develop accurate predictive models while ensuring interpretability of results. The study also incorporates synthetic data generation to enhance dataset size and improve model performance.

## Dataset
Clinical datasets sourced from:
- Mendeley Dataset, 2021
- Synthetic dataset (2 million records) generated using SDV (Synthetic Data Vault) based on Mendeley

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- Matplotlib
## Results
Boosting algorithms (XGBoost, LightGBM, CatBoost) outperformed traditional models such as Decision Tree.
The models showed a slight bias toward predicting the positive class, reducing the chances of missing actual disease cases.
XGBoost provided strong performance along with feature importance insights.
LightGBM demonstrated faster training time and computational efficiency.
  
