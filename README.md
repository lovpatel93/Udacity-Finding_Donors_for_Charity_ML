# Udacity-Finding_Donors_for_Charity_ML

As part of my Udacity Data Scientist Nanodegree Project, my job was to implement the additional functionality necessary to successfully complete this project. 

As part of this project, I have to choose the best candidate algorithm from preliminary results and further optimize this algorithm to best model the data. My goal with this implementation was to construct a model that accurately predicts whether an individual makes more than $50,000. This sort of task can arise in a non-profit setting, where organizations survive on donations. Understanding an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with. While it can be difficult to determine an individual's general income bracket directly from public sources, we infered this value from other publically available features.

Dataset for this project: https://archive.ics.uci.edu/ml/datasets/Census+Income

In this project, I employed several supervised algorithms of my choice to accurately model individuals' income using data collected from the 1994 U.S. Census. The following are the supervised learning models which I used:

* Gaussian Naive Bayes (GaussianNB)
* Decision Trees
* Ensemble Methods (Bagging, AdaBoost, Random Forest, Gradient Boosting)
* K-Nearest Neighbors (KNeighbors)
* Stochastic Gradient Descent Classifier (SGDC)
* Support Vector Machines (SVM)
* Logistic Regression

Following three supervised learning models that were appropriate for this problem that I test on the census data:

* Decision Trees
* Support Vector Machines (SVM)
* Ensemble Methods (AdaBoost)

For each model chosen I described the following:

* Real-world application in industry where the model can be applied
* Strengths of the model (when does it perform well)
* Weaknesses of the model (when does it perform poorly)
* What makes the model a good candidate for the problem, given the data


Out of the three models, AdaBoost was the most appropriate for our task based on following reasons:

* It is the classifier that performs the best on the testing data, in terms of both the accuracy and f-score. 
* It also takes resonably low time to train on the full dataset
* By default, Adaboost uses a decision stump i.e. a decision tree of depth 1 as its base classifier, which can handle categorical and numerical data.
