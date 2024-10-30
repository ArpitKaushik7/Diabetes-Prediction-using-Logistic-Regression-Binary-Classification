# Diabetes-Prediction-using-Logistic-Regression-Binary-Classification
# Diabetes Prediction Using Logistic Regression

This project implements a logistic regression model to predict diabetes based on various health metrics. The dataset used for this project is the Pima Indians Diabetes Database.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The goal of this project is to predict whether a person has diabetes using various health-related attributes. The model uses logistic regression, a popular method for binary classification tasks.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Dataset
The dataset used in this project is the **Pima Indians Diabetes Database**, which can be downloaded from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database). The dataset consists of the following columns:
- `Pregnancies`: Number of times pregnant
- `Glucose`: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skin fold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index (weight in kg/(height in m)^2)
- `DiabetesPedigreeFunction`: Diabetes pedigree function
- `Age`: Age (years)
- `Outcome`: Class variable (0 or 1) indicating diabetes presence

## Installation
To run this project, you will need to have Python installed along with the necessary libraries. You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
