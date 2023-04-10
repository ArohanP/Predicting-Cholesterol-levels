# Introduction
The project aims to build a regressor model that predicts the cholesterol level of a person given their weight and BMI. 

# Exploratory Data Analysis
The dataset did not contain any null values. The correlation matrix showed that weight is strongly and positively correlated with the cholesterol level, while BMI is relatively less and negatively correlated with cholesterol level.
The distribution plots show the individual peaks and spread of each column. 

# Development of the model
Multitude of regression models were implemented on the dataset which was first split into **80-20** training and testing sets. **Mean-squared-error** was used as the performance measure
for each model. A dictionary of values was creating indicating each model and its mean-squared-error. 
