# Predictive Analysis of Type 2 Diabetes Risk

## Overview
This project analyzes type 2 diabetes risk using demographic, lifestyle, and medical factors. The goal is to identify which variables are most strongly associated with diabetes diagnosis and to evaluate how predictive analytics can support early risk detection. In addition to supervised learning, the project also uses clustering to identify broader health risk profiles.

## Project Objective
The main objective is to examine how different groups of variables contribute to diabetes risk and to compare predictive models for classifying diabetes diagnosis. The project also explores whether unsupervised learning can reveal meaningful behavioral risk groups.

## Research Questions
1. Which factors are most strongly associated with type 2 diabetes risk?
2. How well can machine learning models predict diabetes diagnosis?
3. Do demographic and lifestyle factors contribute differently than medical variables?
4. Can individuals be grouped into distinct health risk profiles?

## Dataset
The analysis uses a synthetic diabetes dataset containing individual level records related to diabetes diagnosis and associated risk factors. The dataset includes:
* Demographic variables such as age, gender, ethnicity, education, income, and employment status
* Lifestyle variables such as physical activity, diet, sleep, screen time, smoking, and alcohol use
* Medical and clinical variables such as BMI, blood pressure, cholesterol, fasting glucose, HbA1c, and diabetes risk score

The target variable is diabetes diagnosis.

## Methods
The project follows an end to end predictive analytics workflow:

1. Data inspection and quality assessment
2. Exploratory data analysis
3. Correlation analysis and feature comparison
4. Data preprocessing with imputation, encoding, and scaling
5. Logistic regression baseline model
6. Random forest classification model
7. Threshold tuning for classification tradeoffs
8. K means clustering for behavioral risk profiling

## Key Findings
Clinical variables such as fasting glucose and HbA1c were the strongest predictors of diabetes diagnosis. BMI and age also showed meaningful predictive value. Demographic and lifestyle factors contributed less strongly on their own, but still added useful context.

The logistic regression model provided a strong and interpretable baseline. The random forest model improved performance by capturing non linear relationships and interactions between variables. Clustering also revealed distinct health related profiles, showing that people can be grouped into meaningful behavioral risk patterns even without using the diagnosis label directly.

## Why This Project Matters
Type 2 diabetes is a major public health issue, and early identification of risk factors can support prevention strategies. This project demonstrates how predictive analytics can be used not only to classify outcomes, but also to generate insights that may help guide intervention and education efforts.

## Tools and Libraries
This project was completed in Python using:
* pandas
* numpy
* matplotlib
* seaborn
* scikit learn
* scipy

## How to Run
1. Clone or download this repository.
2. Make sure Python 3 and Jupyter Notebook are installed.
3. Install the required libraries listed above.
4. Place the dataset in the correct `data` folder path.
5. Open the notebook file and run top to bottom.

## Example Installation
`pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter`

### Author

Dong Lee
