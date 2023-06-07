## Daily task 06/06/23

# Regression 
* Regression problem is when output variabl is real and continuous value Ex. salary.
* purpose of regression is to see that how much independent variable is affecting the targeted value , Regression is a statastical process which give quite good results.
* Regression models are used for linear and non linear dataset for finding relation between targeted and indepandent variable.

## Type of Regression
1. Linear Regressiom 
* Used for predictive Analysis.
* Linear Regression focuses on **Conditional Probability Distribution** system.
**Conditional probability** is defined as the likelihood of an event or outcome occurring, based on the occurrence of a previous event or outcome.
Conditional probability is often portrayed as the "probability of A given B," notated as P(A|B).
* Danger of **Overfitting**

**Overfitting**: When machine learning algorithms are constructed, they leverage a sample dataset to train the model. However, when the model trains for too long on sample data or when the model is too complex, it can start to learn the “noise,” or irrelevant information, within the dataset. When the model memorizes the noise and fits too closely to the training set, the model becomes “overfitted,” and it is unable to generalize well to new data. If a model cannot generalize well to new data, then it will not be able to perform the classification or prediction tasks that it was intended for. Low error rates and a high variance are good indicators of overfitting. In order to prevent this type of behavior, part of the training dataset is typically set aside as the “test set” to check for overfitting. If the training data has a low error rate and the test data has a high error rate, it signals overfitting.
How to Detect **Overfitting** : There is a method called **K-fold cross validation** process, here K equal sized subset of the data are splited and one fold will test the data and other k-1 fold will train the model test fold is also known as holdout. This process repeats until each of the fold has acted as a holdout fold. After each evaluation, a score is retained and when all iterations have completed, the scores are averaged to assess the performance of the overall model.

2. Polynomial Regression 


4. stepwise Regression 
5. Decision tree Regression 
6. Random forest Regression 
7. Support vector Regression 
8. Ridge Regression 
9. lasso Regression 
10. ElasticNet Regression
11. Bayesian Linear Regression  
