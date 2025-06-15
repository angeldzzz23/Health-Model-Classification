# Health-Model
Supervised learning 
 - Clasification: Predicts a discrete valued output
 - Labels are discrete (categorical)
 - Labels can be binary
 - examplees (e.g sunny)


## Predicting heart disease

A machine learning project that predicts heart disease using various classification algorithms and feature engineering techniques.

uses dataset from: https://github.com/mpourhoma/CS4661/raw/master/Heart_s2.csv

## Dataset Features
- Target Variable: AHD (Angiographic Heart Disease)
- "Yes": Patient has heart disease
- "No": Patient does not have heart disease
- Numerical Features: Age, vital signs, and other biological measurements
- Categorical Features:
   - ChestPain: Type of chest pain experienced
   - Thal: Thalassemia test results

## Methodology 
Classification Algorithms

K-Nearest Neighbors (KNN)

Parameters: k=7
Non-parametric, instance-based learning


Decision Tree

Parameters: random_state=5
Tree-based, interpretable model

Logistic Regression
Parameters: max_iter=400
Linear model for binary classification

## Feature Engineering

One-Hot Encoding: Convert categorical variables to binary format
Feature Combination: Merge numerical and encoded categorical features
Data Splitting: Stratified sampling to maintain class balance

## Evaluation Methods
Train-Test Split: Initial evaluation with 80/20 split
10-Fold Cross-Validation: Robust performance assessment
Accuracy Score: Primary evaluation metric


## Key findings
1. Numerical Features Only: Baseline performance using only continuous variables
2. Full Feature Set: Improved performance by including categorical features via one-hot encoding
3. Cross-Validation: More reliable performance estimates compared to single train-test splits

