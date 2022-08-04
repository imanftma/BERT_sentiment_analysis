# BERT_sentiment_analysis
This project involves building & comparing 2 different approaches for sentiment analysis of tweets. Tweets are scraped using **snscrape** library for different hashtags.
The 2 approaches are:
1. Machine Learning Models (KNN,SVC, Random Forest, Decision Tree, Naive Bayes)</br>
    a.Bag Of Words</br>
    b. TF-IDF </br>
2. BERT (Bidirectional Encoder Representations from Transformers)

Comparison of Accuarcy score & other metrics for both the approaches can be found in the results folder. 

BERT being a contextual model perfomed better than ML models, therefore we used BERT to predict the sentiment on 500k tweets that we scraped from twitter.
The main challenges in this project were
1. Getting/Building unbiased Training Dataset
2. High Processing Power required for BERT

Analysis on the predicted tweets will be done in Qlik Sense and will be updated shortly.
