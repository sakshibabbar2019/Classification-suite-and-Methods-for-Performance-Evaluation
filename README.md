# Classification-suite-and-Methods-for-Performance-Evaluation
Predictive problems requires three main challenges to overcome. First, choosing the right classification algorithm. Second, building a robust building and testing environment for algorithm to learn and thirdly,  picking the appropriate performance metric for evaluation. Here it is explained how these challenges can be addressed. 

Finding the best classification algorithm is a experimental process that depends upon characteristics of data set and the theory of classification algorithms. Most of the time we do not have prior knowledge of data set pattern and behaviour to decide which algorithm will be best suitable for given application data set. To address this difficulty, a general approach is to make a suit of different classification algorithms and apply it on the data set to compare the performance of different algorithms and pick the the one that gives the best performance.  This repository contains a python file that explains how to make a suit of classification algorithms ,evaluate their performace, and picking the the best.

The list of classification algorithms that will be used to make a suit are:

1. Logistic regression

2. Naive Bayes

3. Decision tree

4. K nearest neighbor

5. Support vector Regression

There are different techniques that can use the given data set to create robust learning enviornment and create useful estimates of performance of the classification models. These techniques are: Hold -out, k cross validation, repeated hold-out and Leave one out cross validation. A deep undertsanding of these techniques are demonstrated using a small data set with practical implementation in python. 

Performance metrices such as,  confusion matrix, precision, recall, ROC curve and AUC are also discussed. In order to use these metrices, scikit learn library that supports built-in functionality of these measures are used.
