# CS464 Introduction to Machine Learning
# BBC News Classification Project
- Implemented in Python (Jupyter Notebook)
## Overview

This project aims to develop a model for classifying news into five topics: Business, Entertainment, Politics, Sport, and Tech.

## Dataset

The dataset consists of 2225 real news articles, preprocessed to represent word occurrences. It is split into 1668 news for training and 557 news for testing (validation). 
## Bag-of-Words Representation and Multinomial Naive Bayes Model

The project utilizes the bag-of-words representation and the Multinomial Naive Bayes model for classification.

### 3.1 - Class Distribution Analysis

1. Find the percentages of each category in `y_train.csv` and `y_test.csv` and visualize them with a pie chart.
2. Calculate the prior probability of each class.
3. Analyze the balance of the training set and discuss the potential impact of class imbalance on the model.
4. Determine the occurrences and log ratios of the words "alien" and "thunder" in the training documents labeled as "Tech."

## 3.2 - Multinomial Naive Bayes Model Evaluation

Train a Multinomial Naive Bayes model on the training set and evaluate on the test set. Report accuracy in three decimal points and provide the confusion matrix.

## 3.3 - Multinomial Naive Bayes Model with Dirichlet Prior

Extend the classifier to use a fair Dirichlet prior (additive smoothing) with α = 1. Train and evaluate on the test set, reporting accuracy and confusion matrix.


## 3.4 - Bernoulli Naive Bayes Model

Train a Bernoulli Naive Bayes classifier on the training set and evaluate on the test set. Report accuracy and confusion matrix.

