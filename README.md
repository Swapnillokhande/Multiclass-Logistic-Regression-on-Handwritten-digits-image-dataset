# INTRODUCTION
Logistic Regression is a method for performing predictive analysis by determining the relation between the dependent variable which is categorical or binary in nature and one or more independent variables. This method of regression is used only when the dependent variable is categorical (Yes or No, or 0 or 1). For instance, to identify an email is a spam or not (Yes or no), a logistic regression can be used. The algorithm gives a probability which can be used to translate the output into one of the classes (Yes or No) (Swaminathan, 2018).

# PROBLEM STATEMENT
For the analysis, an MNIST dataset is used which comprises of thousands of images of hand-written digits between 0 and 9. The goal of the analysis is to build a model which can accurately classify the images as one of the digits between 0 and 9. In this problem, logistic regression can be used to classify the digits. However, this problem is a multiclass regression problem where there are 10 output classes (0-9) but Logistic regression is designed to predict only binary classes. Thus, a generalized Logistic regression model needs to be designed which can classy images into 10 classes, thus for this purpose, Softmax Regression is used. Softmax regression is a multinomial Logistic regression method which is used in scenarios which require multiclass classification. This method would assign a probability that a given image belongs to each number between 0 and 9. For instance, the given number is 1, thus the model would assume that the probability of the image containing 1 is 85% but the probability of predicting that image to be 7 is 10% and some smaller probabilities would be assigned to other number summing up to 1 (Gutha, 2018).

# REFERENCES
Swaminathan, S. (2018, March 15). Logistic Regression – Detailed Overview. Retrieved from https://towardsdatascience.com/logistic-regression-detailed-overview-46c4da4303bc

ML Stochastic Gradient Descent. Retrieved from https://www.geeksforgeeks.org/ml-stochastic-gradient-descent-sgd/

Loss Functions. Retrieved from https://ml-cheatsheet.readthedocs.io/en/latest/loss_functions.html

Softmax Regression. Retrieved from http://ufldl.stanford.edu/tutorial/supervised/SoftmaxRegression/

Gutha, K. (2018, June 20). MNIST For Machine Learning Beginners With Softmax Regression. Retrieved from https://datascienceplus.com/mnist-for-machine-learning-beginners-with-softmax-regression/

Multiclass logistic regression from scratch. Retrieved from https://gluon.mxnet.io/chapter02_supervised-learning/softmax-regression-scratch.html

