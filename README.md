# This repository contains machine learning models using NLP (natural language processing) using the following text datasets:

## 1) SMS dataset:

#### Attributes are: 

    1) label
    2) SMS
    
#### Objective: 

To predict if the SMS is ham or spam.

#### Algorithms used:

    1) multinomial Naive Bayes
    2) Logistic regression
    3) Random forest
    
See notebook [here](https://github.com/jayashree8/Machine_learning_NLP/blob/master/Ham%20spam%20NLP/sms%20NLP.ipynb)

## 2) Yelp dataset:

#### Description of the data:

    1) yelp.csv contains the dataset.
    2) Each observation (row) in this dataset is a review of a particular business by a particular user.
    3) The stars column is the number of stars (1 through 5) assigned by the reviewer to the business. (Higher stars is better.) In other       words, it is the rating of the business by the person who wrote the review.
    4) The text column is the text of the review.

#### Objective:

Predict the star rating of a review using only the review text.

#### Algorithms used:

    1) multinomial Naive Bayes
    
See notebook [here](https://github.com/jayashree8/Machine_learning_NLP/blob/master/Yelp%20NLP/yelp%20exercise.ipynb)