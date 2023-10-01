# Machine Learning Diabetes Prediction Model

## Introduction

This machine learning project aims to develop a predictive model for diabetes using laboratory test results, including urea and creatinine levels, lipid profiles, and Body Mass Index (BMI). Early detection and management of diabetes are crucial for preventing complications and improving patient outcomes.

## Dataset

The dataset used for this project was collected from medical records, including information on patients' medical history, laboratory test results, and diabetes classification. The dataset includes the following features:

- Gender
- Age Range
- Urea Levels
- Creatinine Levels
- HbA1c Levels
- Cholesterol Levels
- Triglycerides Levels
- HDL Cholesterol Levels
- LDL Cholesterol Levels
- VLDL Cholesterol Levels
- Body Mass Index (BMI)
- Diabetes Class (Diabetic, Non-Diabetic, Predicted-Diabetic)

## Data Cleaning

The dataset underwent a thorough data cleaning process, including handling duplicates, correcting data format issues, and categorizing age ranges. The cleaned dataset was saved for further analysis and model training.

## Data Preprocessing

Data preprocessing involved scaling the features to ensure uniformity in scale, as different features had different units and ranges. Min-Max scaling was applied to transform the features between 0 and 1. Categorical variables like gender, age range, and diabetes class were encoded for machine learning models.

## Model Training and Evaluation

Several machine learning models were trained and evaluated using cross-validation techniques. The models considered include Logistic Regression, K-Nearest Neighbors, Support Vector Classifier, Random Forest Classifier, and GradientBoosting Classifier.

The GBoost Classifier demonstrated high accuracy and strong performance in predicting diabetes classes.


## Conclusion

This machine learning project showcases the potential of using laboratory test results and BMI to predict diabetes accurately. Early detection and risk assessment can lead to more effective diabetes management and improved patient outcomes.

For more details, explore the code and analysis in the project files
