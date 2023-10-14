# Project Details

- **Author:** [Sachin Khote](https://github.com/sachinkhote)
- **Example:** Diabetes Prediction
- **Data Created:** 14/10/2023
- **Last Modified:** 15/10/2023

# Diabetes Prediction Dataset

## Overview

This dataset is designed for predicting diabetes based on various health parameters. It includes essential features like glucose level, blood pressure, skin thickness, insulin level, body mass index (BMI), pregnancies, age, and diabetes pedigree function. The dataset aims to assist in predicting whether a patient is diabetic or not based on these parameters.

## Dataset Information

- **Source**: [Diabetes Prediction Dataset](https://github.com/sachinkhote/Public_Dataset/raw/main/Diabetes%20Prediction.csv)
- **Format**: CSV
- **Columns**:
  1. **Pregnancies**: Number of times pregnant
  2. **Glucose**: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
  3. **BloodPressure**: Diastolic blood pressure (mm Hg)
  4. **SkinThickness**: Triceps skin fold thickness (mm)
  5. **Insulin**: 2-Hour serum insulin (mu U/ml)
  6. **BMI**: Body mass index (weight in kg/(height in m)^2)
  7. **DiabetesPedigreeFunction**: Diabetes pedigree function
  8. **Age**: Age in years
  9. **Outcome**: Class variable (0 or 1) indicating whether the patient is diabetic (1) or not (0)

## Data Preprocessing

- **Missing Values**: Missing or zero values in columns such as Glucose, BloodPressure, SkinThickness, Insulin, and BMI were replaced with the mean of the respective columns.
- **Data Splitting**: The dataset was split into training (80%) and testing (20%) sets for model evaluation.

## Exploratory Data Analysis (EDA)

- **Correlation Heatmap**: A heatmap was generated to visualize correlations between different features.
- **Data Distribution**: Histograms and density plots were used to understand the distribution of each feature.
- **Outcome Analysis**: A pie chart and bar plot were created to show the distribution of diabetic and non-diabetic patients. Density plots were also used to visualize age-related patterns in diabetic and non-diabetic groups.

## Modelling

- **Classifiers**: Several classifiers were tested using a pipeline, including Logistic Regression, KNeighbors Classifier, Support Vector Classifier (SVC), Decision Tree Classifier, Random Forest Classifier, and Gradient Boosting Classifier.
- **Model Selection**: Random Forest Classifier with a maximum depth of 3 was selected as the final model due to its highest accuracy on the test data.

## Prediction

- **Sample Prediction**: The model can predict diabetes based on new data inputs for parameters like pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age.

## Usage

The dataset and the associated code can be used for research, analysis, and prediction purposes in the domain of diabetes prediction and related healthcare applications.

## Support

For any inquiries, feedback, or issues related to the Car Price Prediction project, please reach out to the project maintainer:

- **Maintainer:** Pranav Prajapati  
- **Email:** -  
- **GitHub:** https://github.com/pranavvp16  

## Contact

For general inquiries, you can contact us at:

- **Email:** [Sachin khote](sachinkhote451@gmail.com)
- **Linkedin:** [profile](https://www.linkedin.com/in/sachin-khote-195570277/)
