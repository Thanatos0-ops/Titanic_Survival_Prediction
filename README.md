# Titanic Survival Prediction

This project uses machine learning to predict the survival of Titanic passengers based on various features such as age, sex, class, and more.

## Overview

- **Dataset**: Titanic dataset from Kaggle.
- **Task**: Predict whether a passenger survived or not.
- **Models Used**: Logistic Regression and Random Forest Classifier.
- **Techniques**: Exploratory Data Analysis (EDA), data preprocessing, and model evaluation.

## Features

The dataset contains the following columns:

- **PassengerId**: Unique ID for each passenger.
- **Pclass**: The class of the ticket the passenger purchased (1st, 2nd, 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings or spouses aboard the Titanic.
- **Parch**: Number of parents or children aboard the Titanic.
- **Ticket**: Ticket number.
- **Fare**: Fare paid by the passenger.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).
- **Survived**: Target variable (1 if survived, 0 if not).

## Getting Started

### Prerequisites

Ensure you have **Python 3.x** installed and the following libraries:
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
- jupyter

You can install the required libraries using `requirements.txt`:
```bash
pip install -r requirements.txt
