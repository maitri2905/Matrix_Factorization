# Matrix_Factorization
Matrix Factorization using Gradient Descent

DESCRIPTION:

Matrix factorization is used to discover the latent features underlying under two different entities. The source code x.py is an implementation of the matrix factorization algorithm in Python using stochastic gradient descent algorithm. 

The intuition behind using matrix factorization to solve this problem is that there should be some latent features that determine how a user rates an item. 
Algorithm creates two metrics of latent feaures matrics with two entites and initializes with some random value and calculate their difference with original matrics and try to minimize it iteratively by using gradient descent approach. 

Algorithm considers the squared errors as a recommendation could be either higher or lower. It also adds biases of different entities.


HOW TO USE:

Algorithm expects the input feature matrics(load from csv), latent features dimension, learning rate (a constant that determines the rate of approaching the minimum), regularization (to avoid overfitting) and number of iterations to minimize the difference.
