# Predicting Housing Prices
This repository contains code and associated files for developing an algorithm to predict housing prices using supervised and unsupervised machine learning techniques.

### Project Overview
This project aims to build a model that predicts house prices based on various characteristics. The work is divided into two phases:

**Classification Task**: Determines whether a house is expensive or not.
**Regression Task**: Predicts the exact price of a house.
The project follows a standard machine learning workflow, including understanding the problem context, data exploration and cleaning, data preprocessing, model training, and performance evaluation. The objective is to provide clients with accurate and efficient predictions to aid in their decision-making process.

### Classification
1_Model_housing.ipynb: Begins with a "dummy" model to establish a baseline. Then, a decision tree classifier is used, refined using grid search and pipelines.
2_Model_housing_Categorical.ipynb: Handles categorical features using OneHotEncoder.
3_Model_Housing_complete.ipynb: Combines all steps into a comprehensive pipeline that processes numerical and (un)ordered categorical features.
### Regression
models_testing.ipynb: Applies decision tree and random forest regressors to the housing dataset.
Model_testing_and_feature_selection.ipynb: Compares R² score and RMSE of several models and explores feature selection methods (KBest, RFE, Variance Threshold).
