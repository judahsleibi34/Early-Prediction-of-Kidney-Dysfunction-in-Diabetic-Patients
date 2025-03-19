# Early Prediction of Kidney Dysfunction in Diabetic Patients: 

## Overview
This project focuses on the early prediction of kidney dysfunction in diabetic patients by analyzing key health indicators such as Fasting Blood Sugar (FBS) and Creatinine levels. Using machine learning models, the study aims to identify patterns and risk factors associated with early-stage kidney dysfunction. The dataset consists of 499 samples with 13 features, which underwent rigorous preprocessing and analysis to improve model performance.

## Dataset Overview
The dataset includes the following key features:

1. Fasting Blood Sugar (FBS): A critical indicator of diabetes.

2. Creatinine Levels: A key marker for kidney function.

3. Gender: Analyzed to understand gender-specific trends.

4. Other Health Metrics: Additional features contributing to the analysis.

## Data Preprocessing
The dataset was processed in three key stages to ensure high-quality input for machine learning models:

1. Cleaning
Handled missing data and outliers to ensure data integrity.

Identified and addressed inconsistencies in the dataset.

2. Integration
Created two versions of the dataset:

Version 1: Outliers were dropped, resulting in a dataset of size 310x13.

Version 2: Outliers were replaced with mean values, resulting in a dataset of size 496x13.

3. Transformation
Analyzed gender-specific distributions of Creatinine and Fasting Blood Sugar levels.

Addressed gender imbalance to improve model performance.

## Key Findings
Gender-Specific Trends:

Females tend to have higher Creatinine and Fasting Blood Sugar levels compared to males.

Diabetic women exhibit a higher rate of early-stage kidney dysfunction compared to men.

Impact of Data Preprocessing:

The first dataset (outliers dropped) showed reduced performance due to gender imbalance.

The second dataset (outliers replaced with mean values) maintained the original distribution, leading to more consistent and reliable results.

## Model Performance
The following machine learning models were applied to the two datasets, yielding the following infection rate predictions:

### Random Forest
First Dataset (Outliers Dropped): 98.39% accuracy.

Second Dataset (Outliers Replaced with Mean Values): 98.39% accuracy.

### KNN Model
First Dataset (Outliers Dropped): 90.53% accuracy.

Second Dataset (Outliers Replaced with Mean Values): 95.48% accuracy.

## Technologies Used
Programming Language: Python

## Libraries:

1. Scikit-learn (for machine learning models).

2. Pandas (for data manipulation and analysis).

3. NumPy (for numerical computations).

## Data Cleaning and Analysis Tools:

Outlier detection and handling.

Gender-specific data transformation.

Repository Structure
Copy
kidney-dysfunction-prediction/
├── data/                           
│   ├── raw_data.csv                
│   ├── cleaned_data_v1.csv          
│   └── cleaned_data_v2.csv          
├── notebooks/                       
│   └── kidney_dysfunction_analysis.ipynb  
├── README.md                      
├── requirements.txt                
└── visuals/                        
    ├── gender_distribution.png     
    ├── model_performance.png       
    └── outlier_analysis.png         

## Conclusion
This project demonstrates the effectiveness of machine learning models in predicting early-stage kidney dysfunction in diabetic patients. By analyzing Fasting Blood Sugar and Creatinine levels, the study highlights gender-specific trends and the importance of proper data preprocessing. The findings can assist healthcare professionals in early diagnosis and intervention.

## Future Work
Incorporate additional health metrics (e.g., blood pressure, cholesterol levels) to improve prediction accuracy.

Explore deep learning models for more complex pattern recognition.

Conduct a larger-scale study with a more diverse dataset.

## Data Owner
For questions or access to the dataset, please contact:
Majdi Owda
Email: majdi.owda@aaup.edu

