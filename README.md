# Twitter Sentiment Analysis




This project focuses on developing automated methods for achieving accurate twitter sentiment classification on the NLP Disaster Tweets dataset (available on Kaggle [here](https://www.kaggle.com/c/nlp-getting-started)). This project features an implementation of the Naive Bayes algorithm as well as a deep bidirectional long-short-term memory (LSTM) network. The models were evaluated on the basis of the macro-averaged F1 scores, and the latter model was able to acheive a score of 0.80171 which, as of 04/11/21, was good enough to place in the top 30% of submissions.


## Table of Contents

1. [Setup](https://github.com/izwauld/Twitter-Sentiment-Analysis#setup)
2. [Text Normalization](https://github.com/izwauld/Twitter-Sentiment-Analysis#text-normalization)
3. [Building the Naive Bayes Classifier](https://github.com/izwauld/Twitter-Sentiment-Analysis#building-the-naive-bayes-classifier)
4. [Naive Bayes Results](https://github.com/izwauld/Twitter-Sentiment-Analysis#naive-bayes-results)
4. [Building the BDRNN](https://github.com/izwauld/Twitter-Sentiment-Analysis#building-the-bdrnn)
4. [BDRNN Results](https://github.com/izwauld/Twitter-Sentiment-Analysis#bdrnn-results)
5. [Conclusions/Future Work](https://github.com/izwauld/Twitter-Sentiment-Analysis#conclusions-future-work)



The task set out in the initial specification was to develop a model that is able to distinguish when a tweet is related to a disaster and when it is not. Thus, the task is a binary classification problem. 
 
