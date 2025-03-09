# Early Prediction of Kidney Dysfunction in Diabetic Patients

## Overview
This project investigates the early prediction of kidney dysfunction in diabetic patients by analyzing Fasting Blood Sugar 
and Creatinine levels using machine learning models. The study leverages a dataset consisting of 499 samples with 13 features, 
undergoing rigorous preprocessing and analysis to improve model performance.

## Data Preprocessing

The dataset was processed in three key stages:

1. Cleaning: 
Handling missing data and outliers.

2. Integration: 
Creating two versions of the dataset:

  One where outliers were dropped, resulting in a dataset of size 310x13.
  One where outliers were replaced with mean values, resulting in a dataset of size 496x13.

3. Transformation: 
Analyzing gender-specific distributions of Creatinine and Fasting Blood Sugar levels.

## Key Findings

Females tend to have higher Creatinine and Fasting Blood Sugar levels compared to males.
Gender imbalance in the first dataset affected model performance, while maintaining original distribution in the second dataset led to more consistent results.
Diabetic women exhibit a higher rate of early-stage kidney dysfunction compared to men.

## Model Performance

The machine learning models applied to the two datasets yielded the following infection rate predictions:

Random forest:
First dataset (outliers dropped): 98.39%
Second dataset (outliers replaced with mean values): 98.39%

KNN model:
First dataset (outliers dropped): 90.53%
Second dataset (outliers replaced with mean values): 95.48%

Technologies Used

Python
Machine Learning Libraries (e.g., Scikit-learn, Pandas, NumPy)
Data Cleaning and Analysis Tools

## Data owner: 
majdi.owda@aaup.edu
