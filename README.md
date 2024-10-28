# Fake News Detector

## Introduction
Given the proliferation of misinformation online, detecting and mitigating against fake news has become a pressing issue. The rapid growth of social media has amplified this problem, making it increasingly challenging for social media platforms to moderate potentially harmful content while upholding the principles of free speech and expression.

In this project, I create a fake news detector using feature engineering and machine learning. 

By Funmi Looi-Somoye
## Requirements
- Pandas
- NumPy
- Matplotlib
- sklearn

- Dataset: news_articles.csv
- Dataset Source: https://www.kaggle.com/datasets/ruchi798/source-based-news-classification

## Contents
##### (1) FakeNews_DatasetCleansing.ipynb 
Python notebook to investigate the dataset and perform data cleansing to remove missing values and duplicate records.

##### (2) FakeNews_CredibilityAnalysis.ipynb 
Python notebook to investigate the proportion of fake to real news in the dataset and the most and least credible news sources.

##### (3) FakeNews_KeywordsLength.ipynb 
Python notebook to investigate the top 5 keywords associated with fake news articles and the average title and text length for real and fake news articles.

##### (4) FakeNews_FeatureEngineering.ipynb 
Python notebook to predict whether a news article is fake based on news source and title using feature engineering.

##### (5) FakeNews_LogisticRegression.ipynb 
Python notebook to build a logistic regression model to predict if an article is fake based on the article's content.

##### (6) FakeNews_RandomForest.ipynb
Python notebook to create a random forest classifier to predict fake news based on the article title.
