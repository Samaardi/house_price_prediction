# Predicting Housing Prices
This repository contains code and associated files for developing an algorithm to predict housing prices using supervised and unsupervised machine learning techniques.

### Project Overview
This project aims to build a model that predicts house prices based on various characteristics. The work is divided into two phases:

**Classification Task**: Determines whether a house is expensive or not.

**Regression Task**: Predicts the exact price of a house.
The project follows a standard machine learning workflow, including understanding the problem context, data exploration and cleaning, data preprocessing, model training, and performance evaluation. The objective is to provide clients with accurate and efficient predictions to aid in their decision-making process.

### Classification
* [1_Model_housing.ipynb](https://github.com/Samaardi/house_price_prediction/blob/main/1_Model_housing.ipynb): we start with a "dummy" model to get an intuition. Later we use a decision tree classifier, which is later perfected by means of grid search method and pipeline.
* [2_Model_housing_Categorical.ipynb](https://github.com/Samaardi/house_price_prediction/blob/main/2_Model_Housing_Categorical.ipynb): here we deal with categorical features using `OneHotEncoder`.
* [3_Model_Housing_complete.ipynb](https://github.com/Samaardi/house_price_prediction/blob/main/3_Model_Housing_complete.ipynb): here we put all together in a pipeline able to deal with all kinds of features, namely numerical, (un)ordered categorical.

### Regression
* In [models_testing.ipynb](https://github.com/Samaardi/house_price_prediction/blob/main/models_testing.ipynb) we apply decision tree and random forest regressors to our housing dataset
* In [Model testing and feature selection.ipynb](https://github.com/Samaardi/house_price_prediction/blob/main/Model%20testing%20and%20feature%20selection.ipynb) we compare the R^2 score and the RMSE of several models and apply various feature selections (Kbest, RFE, Variance Threshold)

