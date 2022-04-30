# Neural_Network_Charity_Analysis
## Objective
The purpose of this analysis is to use neural network models to predict successful campaigns among charity applications.

## Pre-processing
First the data was imported into a pandas dataframe. Preprocessing steps include dropping unique ID/name columns, and during optimization additional columns were dropped to reduce noise. Next, categorical columns were grouped by frequency of occurence and and new columns were created with binary data. 

## Modelling
Keras modelling and tensor flow library was used to designed a model. https://playground.tensorflow.org/ was used to visualize the model parameters.

## Results
73% accuracy was achieved with the initial model. Unfortunately, after optimization the model accuracy went from 73% to 72%. Optimization strategies were: dropping noisy columns, changing activation functions, adding more hidden layers, and adding nuerons to those hidden layers. Unfortunately, despite these optimization strategies the model is only 75% accurate.
