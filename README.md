# Prediction-of-Gold-Recovered-from-Gold-Ore

In this project we will prepare a prototype of a machine learning model for Zyfra. 
The company develops efficiency solutions for heavy industry. 
The model should predict the amount of gold recovered from gold ore.

## Framework Steps
1. _Data Preparation_
  * Upload libraries
  * Preprocessing
  * Merging Strategy
2. _Exploratory Data Analysis_
  * Missing Values
  * Concentrations of Metals
  * Feed Particle Size Distributions Comparison
  * Total Concentration Analysis
3. _Building a Model_
  * Split data
  * SMAPE value function
  * GridSearch and hyperparameter tuning for Decision Tree Regressor
  * GridSearch and hyperparameter tuning for Random Forest Regressor
  * Dummy Regressor

The final results of the sMAPE comparing several models are shown below:


| Model                                     | sMAPE |
|-------------------------------------------|-------|
| Dummy Regressor                           | 3.42  |
| Decision Tree Regressor                   | 4.53  |
| Random Forest Regressor                   | 3.30  |
