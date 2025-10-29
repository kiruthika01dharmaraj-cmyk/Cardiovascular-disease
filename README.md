# Cardiovascular-disease
Machine Learning Project
## Problem Statement: 
The CAIR-CVD dataset collected from multiple hospitals in bangaladesh during the period JAN 2024-JAN 2025 to identify the individual with high risk at cardiovascular disease.
## OBJECTIVE: 
To build a machine learning project that identify the individual with high risk at cardiovascular disease.
## OUTCOME: 
- A trained and validated machine learning model capable of predicting CVD risk with high accuracy.
- Sample input: Age, gender, systolic_BP, Diastolic_BP
- Sample output: Predict CVD Risk
## Type of Problem
- The Target variable CVD_RISK represents whether the person is at risk or not at risk of cardiovascular disease.
- Hence the goal is to classify individuals into one of two categories
- BINARY CLASSIFICATION

## STAGE 1
# INITIAL EDA ():
- Display Null Values
- NUMERICAL COLUMNS
- CATEGORICAL COLUMNS

## Algorithm Planned to use
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine
- K-Nearest Neighbours

## STAGE 2
- EDA (visualization) & Pre-Processing
- Filling Missing Values (Fillna()) method
- Handling Missing Values
- Removing All Duplicates
- Handle missing values
- Check for missing values
- Find a MEAN MEDIAN MODE
- Shape before removing outliers
- Boxplot before removing outliers
- Remove outliers using Z-score
- Shape after removing outliers
- Boxplot after removing outliers
- Skewness before removing outliers
- Skewness after removing outliers
- Visualization before skewness
- Visualization after Skewness
- UNI VARIATE ANALYSIS
- BI VARIATE ANALYSIS
- MULTI VARIATE ANALYSIS

  ## STAGE 3
  - Feature Selection and Model Building
  - Feature Engineering
  - Feature Transformation
  - Feature Scaling
  - Feature Creation
  - Feature Selection
  - MODEL BUILDING

## STAGE 4
 - Compare different model
 - Visualization
 - Hyper Parameter Tuning --> Gridsearch CV
 - Evaluate the Tuned Model on Test Data
   
## FUTURE ENHANCEMENT
- Collect more recent and balanced dataset.
- Implement advanced models such as XGBoost
- Deploy the model as a wed or mob application for real time risk prediction
- Integrate clinical data for more accurate results

## CONCLUSION
- The Logistic Regression model acheived the highest accuracy (60%) and produced stable results.
- The model is interpretable, efficient and generalizes well, making it suitable for healthcare prediction.
- Therefore, Logistic regression was selected for further optimization and refinement.



