# Diabetes Risk Classification with Discriminant Analysis

## Overview
This repository contains a statistical report and R code for predicting diabetes risk using Linear Discriminant Analysis (LDA). The project serves as a public-health screening initiative aimed at identifying adult women at high risk for diabetes based on various clinical and demographic measurements.

## Dataset
The analysis utilizes the Pima Indians Diabetes Dataset, a well-known public dataset provided by the R MASS package. 
* Target Variable: type (Tested positive or negative for diabetes).
* Predictors: Continuous medical measurements including glucose concentration, blood pressure, body mass index (BMI), age, number of pregnancies, skin thickness, and diabetes pedigree function.

## Methodology
Linear Discriminant Analysis (LDA) was chosen as the optimal classification framework. LDA is specifically designed to handle continuous numerical predictors and find the best linear combination of these features to maximize the separation between clinical groups (diabetic vs. non-diabetic). 

## Key Findings
* Model Performance: The LDA model achieved a robust 79.82% overall accuracy on unseen test data (compared to 77.00% on the training set).
* Feature Importance: By scaling the data and extracting standardized coefficients, Plasma Glucose Concentration was identified as overwhelmingly the strongest predictor of diabetes risk, followed by the pedigree function, age, and BMI.
* Clinical Application: The model translates raw medical measurements into a unified risk scoring system. By analyzing posterior probabilities, it can identify confident predictions for immediate intervention, as well as borderline cases that require secondary diagnostic testing.

## Tech stack
* Language: R
* Libraries: MASS, ggplot2, psych
* Framework: Quarto

## Author
Dimitrios Kostinis Undergraduate Student at Department of Mathematics, NKUA

**[Click here to view the full rendered HTML report](https://dimitriskost.github.io/lda-diabetes-risk-classification/DA_code.html)**
