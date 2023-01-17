
# 1.  Introduction

A term deposit is a key product offered by banks and an effective marketing campaign can play a crucial role in its sales success.
This project aims to predict the outcome of phone calls made by a bank to potential long-term deposit clients. The results of this project will assist managers in prioritizing and selecting customers to contact during future marketing campaigns.

# 2.  Problem and Dataset

The problem is approached as a binary classification problem, with the goal of predicting which clients are more likely to subscribe for a term deposit.

The dataset [[link]](https://archive.ics.uci.edu/ml/datasets/bank+marketing#) used in this project was collected from the UCI Machine Learning Repository. The dataset contains information on direct marketing campaigns made by a Portuguese banking institution between May 2008 and November 2010, with a total of 41,188 records and 21 fields. The classification goal is to predict whether the client will subscribe (1: yes;  0: no) to a term deposit.


# 3. Usage

- Download or clone this project
- Run [the Jupyter notebook](https://nbviewer.org/github/khanhvynguyen/Term_Deposit_Prediction_ML/blob/main/term_deposit_prediction.ipynb), which walks through:
  + Exploratory Data Analysis (EDA), Pre-processing
  + Modeling: Logistic regression, [XGBoost](https://xgboost.readthedocs.io/en/stable/), [LightGBM](https://lightgbm.readthedocs.io/en/latest/Parameters.html)
  + Evaluation: Accuracy, F1 score
  + Interpret model: [SHAP](https://github.com/slundberg/shap)
- Use the trained models to predict the outcome of new phone calls.
