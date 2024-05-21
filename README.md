 Predtic
 ive-Modeling-in-agriculture-for-farmer

# Crop Selection Project

## Overview

This project aims to assist farmers in selecting the best crop for their fields based on soil measurements. It leverages machine learning techniques, specifically logistic regression, to predict crop selection using four essential soil measures: nitrogen content ratio (N), phosphorous content ratio (P), potassium content ratio (K), and pH value of the soil (ph).

## Usage

### Required Libraries

The following libraries are required to run the project:
- pandas
- scikit-learn

### Data Loading and Preprocessing

The dataset 'soil_measures.csv' is loaded using pandas. Missing values in the dataset are checked and handled appropriately.

### Data Splitting

The dataset is split into feature (X) and target (y) sets. The target set consists of multi-class labels representing different crop types.

### Model Training and Evaluation

A logistic regression model is trained for each feature (N, P, K, ph) individually. The F1 score, which is the harmonic mean of precision and recall, is used to evaluate the performance of each model.

### Results

The F1 score for each feature is calculated, and the feature with the highest F1 score is identified as the best predictive feature. In this case, the potassium content ratio (K) produced the best F1 score.

## Conclusion

This project demonstrates the application of machine learning techniques in agriculture, specifically in predicting crop selection based on soil measurements. By utilizing logistic regression models trained on individual soil measures, farmers can make informed decisions about crop selection, leading to improved crop yield and profitability.

