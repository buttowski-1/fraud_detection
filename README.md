Bank Term Deposit Subscription Prediction using XGBoost
Project Overview

This project aims to predict whether a bank customer will subscribe to a term deposit based on historical marketing and customer data.
The dataset is highly imbalanced, with far fewer customers subscribing compared to those who do not.

The solution uses XGBoost with imbalance handling techniques and focuses on business-relevant evaluation metrics rather than just accuracy.

Problem Statement

Banks run large-scale marketing campaigns, but contacting uninterested customers leads to:

High operational costs

Low conversion rates

The goal is to identify potential subscribers in advance, so marketing efforts can be targeted efficiently.


Dataset

Source: Bank marketing dataset

File: data/bank.csv

Target variable:

y = 1 → Customer subscribed

y = 0 → Customer did not subscribe

Challenge: Severe class imbalance (~11% positive class)

Project Architecture

The overall workflow is shown below:

Data loading and inspection

Data preprocessing and encoding

Train–test split with stratification

Handling imbalance using SMOTE

Model training using XGBoost

Evaluation using multiple metrics  

Approach

Converted categorical variables using one-hot encoding

Preserved class distribution using stratified train–test split

Applied SMOTE to balance the training data

Trained an XGBoost classifier

Evaluated performance using:

Precision

Recall

F1-score

ROC-AUC

Focused on minority class (subscribers) performance


Model Performance

Key results on test data:

Accuracy: ~88%

ROC-AUC: ~0.89

Recall (Subscribers): ~0.43

F1-score (Subscribers): ~0.46

The high ROC-AUC indicates good class separation, while moderate recall highlights the trade-off in imbalanced classification problems.
