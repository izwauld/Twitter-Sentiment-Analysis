# Twitter Sentiment Analysis


This project focuses on developing automated methods for achieving accurate twitter sentiment classification on the NLP Disaster Tweets dataset (available on Kaggle [here](https://www.kaggle.com/c/nlp-getting-started)). This project features an implementation of the Naive Bayes algorithm as well as a deep bidirectional long-short-term memory (LSTM) network. The models were evaluated on the basis of the macro-averaged F1 score, and the latter model was able to acheive a score of 0.80171 which, as of 04/11/21, was good enough to place in the top 30% of submissions.

## Setup

The following tools/dependencies were used in the project:
* [Python](https://www.python.org/) - version 3.7.3
* [Tensorflow](https://www.tensorflow.org/) - high-level machine learning framework, version 2.3.0
* (recommended) [Anaconda](https://www.anaconda.com/) - Data science distribution (comes with Jupyter notebook), version 4.7.5 (Jupyter notebooks are super helpful!)
* [NLTK](https://www.nltk.org/) - natural language processing toolkit for Python, version 3.4
* [NumPy](https://pypi.org/project/pydub/) - scientific computing package for Python, version 1.19.4
* [scikit-learn](https://librosa.github.io/librosa/) - popular machine learning toolkit for Python, version 0.20.3

## Running the notebooks

Firstly, make sure to download the training and testing datasets (`train.csv`, `test.csv`) from the Kaggle Competition page [here](https://www.kaggle.com/c/nlp-getting-started/overview). Then, with the `train.csv` and `test.csv` files, the notebooks can be run as-is. 

A full walkthrough of the code is given within the notebooks themselves.
