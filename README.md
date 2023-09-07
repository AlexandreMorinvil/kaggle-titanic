# Kaggle Titanic Competition Solution

[![Kaggle](https://img.shields.io/badge/Kaggle-Competition-blue)](https://www.kaggle.com/c/titanic)

This repository contains my solution for the Kaggle Titanic competition. In this competition, the goal is to predict the survival status (1 for survived, 0 for not survived) of passengers on the Titanic based on various features such as age, gender, class, and more.

## Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Exploration Draft](#exploration-draft)
- [Solution](#solution)
- [Conclusion](#conclusion)

## Overview

Welcome to my Kaggle Titanic Competition solution! In this competition, the challenge is to predict the survival status of passengers aboard the RMS Titanic based on a set of features such as age, gender, socio-economic class, and more. This competition serves as an excellent entry point for data science enthusiasts, offering an opportunity to apply machine learning techniques to a real-world historical event.

The sinking of the Titanic is a well-known tragedy, and this competition asks a fundamental question: What factors influenced a passenger's chances of survival? Through data analysis and machine learning, I have crafted a solution that aims to answer this question accurately.

In this repository, you will find my code, methodologies, and insights into the Kaggle Titanic competition. It is precisely with this goal in mind that I completed this project. In the solution provided, I have explored the dataset, engineered features, preprocessed the data, tested various machine learning models, and fine-tuned them to achieve the best possible prediction accuracy. 

This README serves as a guide to understanding my solution and how to consult it. Feel free to explore the various sections to get an in-depth view of my approach, and don't hesitate to reach out if you have any questions or suggestions for improvement.
Let's dive into the details of my solution and discover what factors determined survival on that fateful night aboard the Titanic!

## Data

Explain the dataset used for this competition. Include a link to the Kaggle competition page where users can download the data.

### Data Files

The dataset used in this problem include the following file :

- `train.csv`: Training dataset.
- `test.csv`: Test dataset.
- `gender_submission.csv`: Example of a dummy submission format to Kaggle.

### Data Columns

The columns present in the dataset and what each column represents is described on the Kaggle website : https://www.kaggle.com/competitions/titanic/data

## Exploration Draft

As this is an introductory project, a first exploratory draft Jupyter Notebook named "exploratory_draft" contains my first attempt to tackle this problem. This notebook contains my first attempts at data exploration, feature engineering and predictions using a Decision Tree classifier and a Random Forest Classifier. 

Some of the strategies used were :
- Using One Hot encoder to handle categorical data
- Using a Decision Tree Classifier
- Using a Random Forest Classifier
- Trying to engineer the highest number of features possible (Which ended up not being an optimal approach)

Using this very simplistic approach, the best result achieved was 77% accuracy (using a decision tree classifier).

## Solution

After this first round experimenting in the exploratory draft phase, I started anew, equiped with my newly acquired knowledge from the first attempt and I created another solution, in the "solution" Jupyter Notebook, that was meant to be more comprehensive and go one step further in the optimisation of the predictions.

Along with some of the strategies of the exploratory draft, some of the new stategies used were :

- Using seaborn to use a more visual approach to data exploration
- More elaborate solutions for data imputation
- More selective data engineering (Using less features, but more relevant ones)
- Normalizing the Numerical features
- Dataset balancing using the SMOTE Oversampling algorithm
- Using three ensemble classifiers : RandomForest, Adaboost, XGBoost
- Stacking classifier

Unfortunately, this more complex approach yielded an accuracy of 74%, which is less than the simplistic approach. That being said, less tweaking was done on this solution once the final results were obtained.

## Conclusion

This competition was an interesting starting point in the world of Data Science. Though I could have been interesting to work further on my solution in order to attempt to reach the threshold of the 80%, I have decided to to settle with this solution and tackle different challenges!