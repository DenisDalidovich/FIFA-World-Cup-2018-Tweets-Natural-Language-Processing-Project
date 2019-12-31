# FIFA-World-Cup-2018-Tweets-Natural-Language-Processing-Project

The purpose of this project is to answer the following question. Given a tweet related to a specific topic or event, can we predict how often a tweet is retweeted based on its content?

In this project, we focus on the dataset that can be downloaded from:

https://www.kaggle.com/rgupta09/world-cup-2018-tweets

This dataset is not a part of any Kaggle competitions. It contains the tweets posted during the FIFA World Cup 2018. Our task is  to prepare the text data from scratch making it suitable for machine learning algorithms, and apply a classifier to predict whether a tweet was retweeted at least two times or not. 

It is shown, that including the hashtags of tweets in a separately vectorized form in addition to vectorizing the words of the main text of all tweets, increases the predictive accuracy of the model. The ExtraTreesClassifier (extremely randomized trees classifier) from scikit-learn was used to perform the classification task. Using this non deep learning algorithm on a relatively large dataet, it is possible to achieve the accuracy of 0.81 on the test set.

