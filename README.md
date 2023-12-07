# Heart Disease Prediction
#### Authors: Johanna Kasenurm, Elisabet Hein

## Motivation and goal of this project
According to the World Health Organization (WHO) heart diseases, also known as cardiovascular diseases (CVDs) are causing the most deaths around the world. CVDs include different heart and blood vessel-related diseases, such as coronary heart disease (CHD), cerebrovascular disease, and rheumatic heart disease (RHD). It is argued that CVDs are among the deadliest diseases in both developed and developing countries. According to WHO CVDs take an estimated 17.9 million lives each year which is about 32% of all deaths globally. However, the chance of survival is higher if the diagnosis is made early enough. The goal of this project is to predict which people are at risk of heart disease.

## Contents of this repository
This repository contains the notebook file of this project (Project.ipynb), the datafile used for this project (heart_statlog_cleveland_hungary_final.csv) and the report of this project which analyses the data and background of this subject (D6_report.pdf).

## Contents of the code
* Checking the quality of the data
* Visualizing and analysing the data
  * Distributions
  * Correlations
  * Relations between heart disease and various features
* Building different prediction models and optimizing them
  * Random forest
  * Decision tree
  * KNN
  * Neural network
* Analysing the results of the models
* Prediction based on user input

## How to replicate this project
* Prepare the data
 * Remove missing values
 * Transform the string values to numeric
 * Replace the column names or titles in the code with your column names if needed (we have used feature importance and this could differ with your dataset)
 * Change the user input part in the code according to your data (we print out a lot of text according to our data)
* Optimize the models as necessary (the parameter values in our models are chosen to give the best results with our data and you might need to change them)
* Run the code
