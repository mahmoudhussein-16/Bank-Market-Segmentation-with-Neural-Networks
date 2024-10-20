# Bank Marketing Campaign Prediction with Neural Networks

This project applies a neural network to predict the outcome of bank marketing campaigns. By analyzing customer data, the model aims to predict whether a client will subscribe to a term deposit.

## Overview

The project uses data from a Portuguese bank’s direct marketing campaigns to build a machine learning model for predicting customer responses. We preprocess the data, handle categorical variables, and use a neural network built with TensorFlow/Keras to classify whether a client will subscribe to a term deposit based on various features.

## Key Features

- **Data Preparation**: Handle missing values and encode categorical data.
- **Modeling**: Train a neural network to classify campaign outcomes.
- **Evaluation**: Assess model performance using accuracy and confusion matrix.

## Steps

1. **Import Libraries**: Load libraries including Pandas, Seaborn, and TensorFlow.
2. **Load and Inspect Data**: Load the dataset and inspect for missing values.
3. **Data Preprocessing**: Handle missing data, label encoding for categorical features, and scaling numeric features.
4. **Model Building**: Build a neural network with dense layers for classification.
5. **Model Evaluation**: Evaluate the model using accuracy, confusion matrix, and other metrics.
