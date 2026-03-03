# Case Study 3: NLP

## Overview
This project focuses on building time series model
We performed predictive modeling and topic modeling.

## Dataset
The dataset is sourced from Kaggle:
Steam Review & Games Dataset
https://www.kaggle.com/datasets/filipkin/steam-reviews

## Methods
- Time series cross-validation
- Feature engineering
- Model selection
  - Logistic regression
  - Random Forest
  - Naive bayes
- Grid search

# Best hyperparameters
- clf__C: 5
- clf__penalty: l2
- vect__ngram_range: (1, 2)
- vect__stop_words: None

## Results
- Accuracy: 0.873
- Regard to topic modeling, since this dataset includes specific types of game review, the outcome really depends on how many number of topics we set. However, we successfully identify the game reviews with 6 topics.
