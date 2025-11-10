# Disaster Tweet Classification

## Problem Description

The problem is to predict which Tweets are about real disasters and which are not. This notebook will be heavily based on the one by Gunes Evitan, which is referenced in the pinned notebook for this Kaggle competition, and will be mainly for my own reference on NLP techniques. 

The data structure is a csv with 5 columns. There is a column for the id of the tweet, the text of the tweet, a keyword from the tweet, and the location the tweet was sent from. The location and keyword may be blank.

The data consists of 7613 tweets, with 3263 tweets for the test set. 

## Exploratory Work

The Jupyter notebook file inside the `jupyter_notebook` folder contains the code for the exploratory data analysis and model training. The `outputs` folder contains the outputs from running the models on the testing data, and the `training_stats` folder contains pickle files of the training stats.

## References

The data cleaning and exploratory data analysis code is heavily taken from Gunes Evitan's pinned notebook for this Kaggle competition. \
[NLP with Disaster Tweets - EDA, Cleaning and BERT](https://www.kaggle.com/code/gunesevitan/nlp-with-disaster-tweets-eda-cleaning-and-bert/notebook)
