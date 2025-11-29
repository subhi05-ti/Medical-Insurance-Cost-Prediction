# Medical-Insurance-Cost-Prediction
## Project Overview

This project focuses on predicting medical insurance costs for individuals based on demographic and health-related factors such as age, gender, BMI, smoking habits, number of children, and region. Using machine learning techniques, the model aims to estimate insurance charges, helping both insurance companies and individuals make informed financial decisions.

🎯 Project Goals

✔ Build a robust machine learning model that predicts individual medical charges.
✔ Perform data preprocessing, including handling missing values, encoding categorical variables, and feature scaling.
✔ Conduct exploratory data analysis (EDA) to understand relationships between features and insurance cost.
✔ Evaluate multiple ML algorithms such as Linear Regression, Random Forest, XGBoost, and Decision Tree.
✔ Optimize model performance using techniques like hyperparameter tuning and cross-validation.

📊 Dataset Information

The dataset typically includes the following features:

            Feature	Description
age               -             	Age of the individual
sex	              -               Gender (male/female)
bmi               -               Body Mass Index
children          -              	Number of dependent children
smoker            -            	  Whether the individual smokes
region            -            	  Residential region (southwest, southeast, northwest, northeast)
charges           -               Medical insurance cost (target variable)


🧼 Data Preprocessing Steps

The following preprocessing techniques are applied:
1.Handling missing values (if any)

2.Encoding categorical variables

  Label Encoding: smoker, sex

  One-Hot Encoding: region

3.Feature scaling (for algorithms sensitive to feature magnitude)

4.Outlier detection using statistical methods

5.Train-test split for model evaluation


📈 Exploratory Data Analysis (EDA)

EDA includes:

1.Distribution plots for age, BMI, and charges
2.Boxplots to examine smoker/non-smoker cost differences
3.Correlation heatmaps
5.Region-wise cost analysis
5.Identifying key drivers influencing insurance charges
6.Smoking status
7.Age
8.BMI

🤖 Machine Learning Models Used    -    Linear Regression


🏆 Accuracy Results
The model got 75% accuracy on "Training data" and 74% accuracy on "Testing data".

