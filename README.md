# Auto_Insurance
Given the training set, this project aims to find the correlation between various ordinal and interval features inorder to figure out the factors that effect the need for an automobile to be re-insured.

The data is cleaned and cleaned data is visualised using distribution plots and bar graphs. Once understood, the following models are applied to the data:
Logistic Regression {simple, w/ lbfgs solver, w/ liblinear solver},\
Random Forest,\
AdaBoost,\
XGBoost,\
Multi-layer Perceptron.

Each model's performance is determined using their AUC and F1 Scores. 
