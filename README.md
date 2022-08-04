# BERT_sentiment_analysis
This project involves building & comparing different approaches for sentiment analysis of tweets. Tweets are scraped using **snscrape** library for different hashtags.
The 2 approaches are:
1. Machine Learning Models (KNN,SVC, Random Forest, Decision Tree, Naive Bayes)
2. BERT (Bidirectional Encoder Representations from Transformers)

Accuarcy score of both the approaches can be found in the results folder

BERT being a contextual model perfomed better than ML models, therefore we used BERT to predict the sentiment on 500k tweets we scraped from twitter.
