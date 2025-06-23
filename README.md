# Marketing A/B Testing: Bayesian vs Frequentist

## Overview
This project performs an A/B test analysis on a marketing dataset using both **Bayesian** and **Frequentist** hypothesis testing methods.
It includes data preprocessing, exploratory data analysis (EDA), and statistical testing to evaluate the effectiveness of ad exposure.

## Notebook
https://github.com/refuel-code-135/stat-abtest-marketing-bayes-frequentist/blob/main/notebooks/abtest.ipynb

## Dataset

The dataset used in this project can be downloaded from Kaggle:

https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing

After downloading, please place the file marketing_AB.csv in the data/ directory.

## Set Up Analysis environment
```
export CONDA_ENV=marketing-abtest

# Create and activate a new conda environment
conda create -n $CONDA_ENV python=3.10
conda activate $CONDA_ENV

# Install required Python packages
pip install -r requirements.txt

# Start notebook
jupyter lab
```
