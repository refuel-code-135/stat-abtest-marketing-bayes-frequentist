# Marketing A/B Testing: Bayesian vs Frequentist

## Overview
This project performs an A/B test analysis on a marketing dataset using both **Bayesian** and **Frequentist** hypothesis testing methods.
It includes data preprocessing, exploratory data analysis (EDA), and statistical testing to evaluate the effectiveness of ad exposure.

## Set Up Analysis environment
```
conda create -n marketing-abtest python=3.10
conda activate marketing-abtest

pip install jupyterlab pandas numpy lightgbm matplotlib seaborn scikit-learn shap pyarrow optuna xgboost


jupyter lab
```

## Dataset

The dataset used in this project can be downloaded from Kaggle:

https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing

After downloading, please place the file marketing_AB.csv in the data/ directory.
