# SMS Spam Classifier

This is a simple machine learning project for classify SMS message into spam or not spam. It is done using python and scikit learn library.

## About Project

Many peoples receive spam messages in daily life which is annoying. So this project help to detect those spam messages automaticly. It can be usefull for filter spam in messaging app or email.

The model is trained on a dataset which contains many spam and ham messages. Ham means not spam.

## How it Works

- First the dataset is cleaned and preprocessing is done like removing punctuations and converting to lowercase.
- Then text is converted to numbers using TF-IDF Vectorizer.
- Then the model is trained using Naive Bayes algorithm.
- After training, we can give any message and it will tell if it is spam or not.

## Requirement

- Python 3
- pandas
- numpy
- sklearn
- matplotlib (optional)


