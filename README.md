# Twitter Sentiment Analysis




This project focuses on developing automated methods for achieving accurate twitter sentiment classification on the NLP Disaster Tweets dataset (available on Kaggle [here](https://www.kaggle.com/c/nlp-getting-started)). The models developed in this project consist of an implementation of the Naive Bayes algorthim as well as deep bidirectional long-short-term memory (LSTM) network. The models were evaluated on the basis of the macro-averaged F1 scores, and the latter model was able to acheive a score of 0.80171 which, as of 04/11/21, was good enough to place in the top 30% of submissions.








The task set out in the initial specification was to develop a model that is able to distinguish when a tweet is related to a disaster and when it is not. Thus, the task is a binary classification problem. 

There were two models developed for this task, one based on the the Naive Bayes algorithm that treats and the other using Deep Learning - specifically, a bidirectional convolutional LSTM 
