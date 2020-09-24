---
layout: post
title:  "Loan prediction "
img: images/project/loan/Thumnail.png
description: "Machine Learning using scikit-learn Design bank loan default database schema in MySQL Use Pandas for feature engineering. Train various models with Gridsearch for loan default prediction Model validation using f1-score"
---


Machine Learning using scikit-learn Design bank loan default database schema in MySQL Use Pandas for feature engineering. Train various models with Gridsearch for loan default prediction Model validation using f1-score. The data is from official website of Lending Club. It has more than 1.6M loan entries and hundreds of features.

The purpose was to build a classifier that can predict loan default risk based on loan application data. 

I applied various technique to prevent overfitting. I did undersampling by boosting and bagging to balance the imbalance data set.In order to build the machine learning models, we need to do the data processing in advance. Firstly, dropping columns that contain too many missing values.

Based on setting different paraemters to compare the optimized models with baseline models. I evaluated models with accuracy score, precision, recall and F1-score.

