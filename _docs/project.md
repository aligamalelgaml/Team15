---
title: Project Methodology 
description: Project explained further
---

# Project Methodology

## Exploratory Data Analysis

### Data variation

Exploring patterns of variation, typical values and outliers is
an important task. We can gain such knowledge by visualizing the variables’ distributions. To examine the distribution
of a categorical variable, we can use a bar chart. And for
continuous variables, histograms and frequency polygons
can be used. To overcome binning bias of histogram and
display all data, we can use swarm plots.

### Covariance

It’s important to study the behavior between variables to
gain useful insights that can be useful for feature selection.
To examine the covariance between categorical and continuous variables we can use a boxplot or violin plot. If both
variables we are interested in are categorical we can use
heatmap or scatterplot. If both are continuous, heatmaps
can be used. Measuring the central tendency mean and median for numerical data and mode for categorical- and measuring spread of data. Examining relationships - plotting for
numerical and two-way-cross-tabulations for categorical.

## Data Preprocessing

### Discretization

Discretization is the process of transforming continuous
data into categorical data. The importance of discretization
is that it helps handling outliers by placing these values into
the lower or higher intervals together with the remaining inlying values of the distribution. Our discretization will be
handled by the file attached to the dataset.


### Feature Scaling
Using a normalization technique (Z-score or min-max normalization) to avoid skew towards high magnitude features.


### Feature Engineering & Selection
Via categorical variables encoding and numerical variables engineering and removing redundant features, then checking for correlated features and training the model with feature selection
and using PCA.


## Modeling
We will be using both Decision Tree and Naive Bayes
for our model and testing which one is more accurate. We
may use LDA for dimensionality reduction. Should we have
the time we may test further methods (not including binary
methods).

## Evaluation 

Evaluation of our model will be done through comparing
the actual outcome grading to the predicted class grading.
In other words, our main measure of success will depend
on the accuracy of our prediction model and it’s ability to
correct it’s predictions with time.

![Evaluation](eval.jpg)