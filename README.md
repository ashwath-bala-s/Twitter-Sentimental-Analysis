# Twitter Sentimental Analysis using Machine Learning

**Introduction:**

In the age of social media, platforms like Twitter have become vital for expressing opinions and sentiments on various topics. Analyzing sentiments expressed in tweets can provide valuable insights for businesses, researchers, and policymakers. This project aims to utilize natural language processing (NLP) techniques to perform sentiment analysis on Twitter data, categorizing tweets based on sentiments.

**Problem Statement:**

The objective of this project is to develop a machine learning model that accurately classifies the sentiment of tweets related to specific topics or events. By leveraging tweet data, including text content the model will learn to identify sentiment patterns and trends.

**Dataset:**

The dataset used for this project has 7,920 records and has the following columns:

id - A unique identifier for each tweet

label - A label indicating whether the tweet is positive or negative (1 = positive, 0 = negative) [Target Variable]

tweet - the text of the tweet

**Project Description:**

• Performed initial data exploration by visualizing tweet frequency, analyzing tweet length distribution, and identifying common words and hashtags.

• Cleaned the tweets by eliminating user mentions, hashtags, URLs, special characters and applied contraction mapping to expand contractions

• Conducted tokenization to split tweets into tokens, removed stop words, and lemmatized the words to their base forms.

• Performed data pre-processing and feature extraction in preparation for model building.

• Developed a Logistic Regression model to classify the sentiments of tweets.

• Achieved an F1 score of 0.77, demonstrating effective sentiment classification.

**Skills:** Machine Learning · Data Pre-Processing · Contraction Mapping · Tokenization · Lemmatization · Feature Extraction · Logistic Regression
