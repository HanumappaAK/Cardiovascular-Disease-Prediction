# Cardiovascular Disease Prediction

This project uses machine learning models to predict the likelihood of cardiovascular disease based on user input. The models used include Logistic Regression, Random Forest, and Gradient Boosting. The application is built using Streamlit, a Python library for creating web applications.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Model Details](#model-details)


## Introduction

Cardiovascular diseases (CVDs) are the leading cause of death globally. This project aims to provide a simple interface for predicting the likelihood of cardiovascular disease using various machine learning models. Users can input their health parameters, and the application will provide a probability of being healthy or having heart disease.

## Features

- User-friendly interface built with Streamlit
- Predict cardiovascular disease using Logistic Regression, Random Forest, and Gradient Boosting models
- Visual comparison of prediction probabilities from different models
- Easy-to-understand disease stage classification

## Usage

1. Open the deployed application [here](https://cardiovascular-disease-detection-62cj.onrender.com/).

2. Enter the required input features in the web interface:
   - Age (in years)
   - Height (in cm)
   - Weight (in kg)
   - Gender
   - Systolic Blood Pressure (mmHg)
   - Diastolic Blood Pressure (mmHg)
   - Cholesterol Level
   - Glucose Level
   - Smoking status
   - Alcohol intake
   - Physical activity

3. Click the buttons to get predictions from the Logistic Regression, Random Forest, or Gradient Boosting models.

4. View the prediction results and the comparison graph of the probabilities.

## Model Details

### Logistic Regression

- Implemented using `SGDClassifier` with `log_loss`
- Uses L1 penalty and a maximum of 1000 iterations
- Suitable for linear decision boundaries

### Random Forest

- Implemented using `RandomForestClassifier` with 10 estimators and entropy criterion
- Provides robust predictions using multiple decision trees
- Suitable for non-linear decision boundaries

### Gradient Boosting

- Implemented using `GradientBoostingClassifier`
- Combines weak learners to form a strong learner
- Suitable for capturing complex patterns in data






