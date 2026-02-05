#### Heart Disease Prediction Model Using Machine Learning
## Problem which i sloved it =

Heart disease is one of the leading causes of death worldwide.
A major challenge in healthcare is the early detection of heart disease, as symptoms are not always visible in the initial stages.

Traditional diagnostic methods:

Are time-consuming

Require expensive medical tests

Depend heavily on expert interpretation

As a result, many patients are diagnosed too late, increasing health risks and mortality.

## To address this problem, this project uses Machine Learning techniques to predict whether a person is likely to have heart disease based on medical and physiological attributes.

# Objective of the Project

The main objectives of this project are:

To analyze patient health data

To build a machine learning model that predicts heart disease risk

To assist doctors and healthcare professionals in early decision-making

✔ Early diagnosis
✔ Reduced medical cost
✔ Improved healthcare outcomes

# Dataset Description

The project uses a structured dataset (heart_disease_data.csv) containing medical information of patients.(data set taken from kaggle)

Key Features:
Feature	Description
age	Age of the patient
sex	Gender (1 = Male, 0 = Female)
cp	Chest pain type
trestbps	Resting blood pressure
chol	Serum cholesterol
fbs	Fasting blood sugar
restecg	Resting electrocardiographic results
thalach	Maximum heart rate achieved
exang	Exercise-induced angina
oldpeak	ST depression
target	1 = Heart Disease, 0 = No Heart Disease
## Methodology

The project follows these steps:

Data Collection & Loading

Load the dataset using Pandas

Data Preprocessing

Handle missing values

Feature selection and scaling

Exploratory Data Analysis (EDA)

Understand data patterns

Analyze relationships between features and target variable

Model Building

Apply machine learning classification algorithms

Train the model on training data

Model Evaluation

Evaluate performance using accuracy and other metrics

## Machine Learning Algorithm Used

This project uses Machine Learning Classification Algorithms, such as:

Logistic Regression / Random Forest (as implemented in the notebook)

These algorithms are well-suited for binary classification problems like:

Heart Disease → Yes / No

## Results

The model successfully predicts the presence of heart disease

Achieves good accuracy on test data

Demonstrates the effectiveness of machine learning in healthcare

## Tools & Technologies Used

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn
