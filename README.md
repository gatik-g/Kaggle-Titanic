# Titanic Kaggle Competition Submission

## Overview

This repository contains my submissions for the Titanic Kaggle competition. In this competition, the goal is to predict whether a passenger survived or not based on various features. I've made two different attempts using different machine learning models.

## Models Used

1. **Logistic Regression**
   - Jupyter Notebook: [Logistic_Regression.ipynb](Logistic_Regression.ipynb)
   - In this notebook, I implemented a Logistic Regression model to predict passenger survival. I preprocessed the data, handled missing values, and trained the model using the training dataset. The notebook contains detailed code and explanations of the steps taken.
   - Accuracy achieved: 76%

2. **Neural Network**
   - Jupyter Notebook: [Neural_Network.ipynb](Neural_Network.ipynb)
   - In this notebook, I attempted to improve the prediction accuracy by using a Neural Network. I designed and trained a simple neural network model using TensorFlow. The notebook includes the architecture, training process, and evaluation metrics.
   - Accuracy achieved: 78%

## Data

- The competition dataset includes two CSV files, `train.csv` and `test.csv`, containing passenger information such as name, age, gender, class, and more. The `train.csv` file includes the target variable, whether the passenger survived or not, while the `test.csv` file lacks this information, and our models aim to predict it.
- You can also get these from the competition page: https://www.kaggle.com/c/titanic
- Feel free to use and modify the code for your own analysis or submit your improvements!
