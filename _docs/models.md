---
title: Machine Learning Models
description: A brief overview of the output of our used models.
---

# Machine Learning Models

## Naïve Bayes Model

Naive Bayes algorithms is a classification technique based on applying Bayes’ theorem under the assumption that all the events are independent to each other. In Bayesian classification, the main interest is to find the probability of a class given some other observed feature, P(A\|Feature). We can express this as follows; P(A\|Feature) = P(A) * P(Feature\|A) / P(Feature)

P(A\|Feature) is the probability of a class given a certain feature. P(A) is the probability of a class. P(Feature\|A) is the probability of a feature given a certain class. P(Feature) is the probability of a feature.


## KNN Model

K-nearest neighbour is a lazy non-parametric machine learning algorithm which can be used for both classification as well as regression predictive problems. Ut works by feature similarity to predict values, in other words, a new data point will be assigned a value based on how closely it matches the points in the training set. We can understand its working with the help of following steps −


## Observed Advantages of Each Model

- Naive Bayes is a linear classifier while KNN is not; It tends to be faster when applied to big data. In comparison, KNN is usually slower for large amounts of data, because of the calculations required for each new step in the process. 

     - In general, Naive Bayes is highly accurate when applied to big data. Meanwhile as the value of k in KNN increases, the error rate decreases until it reaches that of the ideal Bayes (k→∞).  

- Naive Bayes can suffer from the zero probability problem; when a particular attribute's conditional probability equals zero, Naive Bayes will completely fail to produce a valid prediction. This has been migitated in our code by using a Laplacian estimator.      

