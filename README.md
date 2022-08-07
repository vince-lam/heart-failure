# Comparison of FLAML Optimised Classification Machine Learning Models for Predicting Heart Failure

Code for Applied Machine Learning (YSJ second year module) technical report.

Dataset is available at:
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

### Abstract:

This paper compares several of the most popular and successful classifiers used in machine learning competitions for the early diagnosis of heart disease. Heart disease is one of the leading causes of death in the world. The dataset consists of 918 records collated from several sources. Several python packages were used to automate the machine learning process, including data visualisation (pandas-profiling and dabl) and hyperparameter optimisation (Microsoft’s FLAML). The selected classifier algorithms were logistic regression, random forest, extreme gradient boosting (XGBoost), Light Gradient Boosting Machine (LightGBM), and Categorical Boosting (CatBoost). Several resampling (undersampling, oversampling, and SMOTE oversampling) and feature engineering techniques (one-hot encoding, scaling, and binning) were explored. The best performing model was a random forest after hyperparameter optimisation via a grid search, giving a mean recall score of 0.92.