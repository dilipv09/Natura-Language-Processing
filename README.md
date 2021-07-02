# Natural-Language-Processing

# Problem Statement
The objective is to identify the tweet has a positive sentiment or a negative one

# Dataset description
The sample dataset from NLTK is separated into positive and negative tweets. It contains 5000 positive tweets and 5000 negative tweets exactly. The exact match between these classes is not a coincidence. This dataset has been manually annotated and serves to establish baselines for models quickly. The intention is to have a balanced dataset. That does not reflect the real distributions of positive and negative classes in live Twitter streams. It is just because balanced datasets simplify the design of most computational methods that are required for sentiment analysis.

# Overview
I. Preprocess raw text
Data preprocessing is one of the critical steps in any machine learning project. It includes cleaning and formatting the data before feeding into a machine learning algorithm. For NLP, the preprocessing steps are comprised of the following tasks:

* Tokenizing the string
* Lowercasing
* Removing stop words and punctuation
* Stemming

II. Implement logistic regression for sentiment analysis on tweets. Given a tweet, we will decide if it has a positive sentiment or a negative one. Following steps to be performed:
* Extract features for logistic regression given some text
* Implement logistic regression from scratch
* Apply logistic regression on a natural language processing task
* Test using your logistic regression
* Perform error analysis
* Predict with your own tweet
