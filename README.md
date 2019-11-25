# Sentiment Analysis on Tweets

Dataset Information

We use and compare various different methods for sentiment analysis on tweets (a binary classification problem). The training dataset is expected to an excel file of type `tweet_id,sentiment,tweet` where the `tweet_id` is a unique integer identifying the tweet, `sentiment` is either `1` (positive) or `0` (negative), and `tweet` is the tweet enclosed in `""`. Similarly, the test dataset is an excel file of type `tweet_id,tweet`. 

Libraries

There are some general library requirements for the project : 
* `numpy`
* `scikit-learn`
* `scipy`
* `nltk`

The library requirements specific to some methods are:
* `keras` with `TensorFlow` backend for Logistic Regression

   Decision Tree
1. Run `decisiontree.py`. With `TRAIN = True` it will show the accuracy results on 10% validation dataset.

   Random Forest
2. Run `randomforest.py`. With `TRAIN = True` it will show the accuracy results on 10% validation dataset.

   SVM
3. Run `svm.py`. With `TRAIN = True` it will show the accuracy results on 10% validation dataset.
