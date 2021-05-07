# Ensemble Learning
Suppose you ask a complex question to thousands of random people, then aggregate their answers. In many cases, you will find that this aggregated answer is betterthan an expert's answer. This is called the wisdom of the crowd. Similarly, if you aggregate the predictions of a group of predictors (such as classifiers or regressors), you will often get better predictions than with the best individual predictor. A group of predictors is called an ensemble and the techniqueis called ensemble learning, and itsalgorithm is called an ensemble method.

# Relation of Bias & Variance
To  understand the  importance  of  Ensemble  Learning,  we  need  to  first understand  what causes these errors in the model.

**Bias error:**
It quantifies how much on average are the predicted values different from the actual values.  A  high  bias  error  means that we  have anunder-performing model that keeps on missing important trends.

**Variance:**
It quantifies how are the predictions made on the same observation different from each other. A high variance model will overfiton the training data and perform badly on any observation beyond training.

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/Bias.PNG)

The following diagram will giveus  more  clarity  (Assume  that red  spot  is the  real  value  and blue dots are predictions):

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/variance.PNG)

A goodmodel should maintain a balancebetweenbiasand varianceerrors. This is known as thetrade-off managementof bias-variance errors.

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/good%20model.PNG)

# Types of Ensemble Learning

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/type.PNG)

**1. Sequential Ensemble learning (Boosting)**
Boosting is   an ensemble   meta-algorithm where   base   estimators   are   generated sequentially and convert weak learners to strong learners

Example: Adaboost, Stochastic Gradient Boosting.

**2. Parallel Ensemble Learning (Bagging)**
Baggingis a meta-algorithm intended to improve the strength and accuracy of a model by generating base learners in parallel

Algorithms: Random Forest, Bagged Decision Trees, Extra Trees

**3. Stacking & Blending**
It consists of stacking the outputof an individual estimator and use a classifier to compute the final prediction.

Example: Voting Classifier

#Notes

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/1.jpg)

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/2.jpg)

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/3.jpg)

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/4.jpg)

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/5.jpg)

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/6.jpg)

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/7.jpg)

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/8.jpg)

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/9.jpg)

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/10.jpeg)

![](https://github.com/kasturi-sahu/Ensemble_Learning/blob/main/11.jpeg)
