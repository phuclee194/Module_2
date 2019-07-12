Variance measures the variation of a single random variable, whereas covariance is a measure of how much two random variables vary together.


Variance is a measure of the variabiloty or spread in a set of data. It is the average squared deviation from the mean score. 

Cocariance is a measure of the extent to which corresponding elements from two sets of ordered data move in the same direction. 

How to create a variance-covariance matrix:

X is an n x k matrix holding ordered sets of data. 

Transform the raw score from matrix X into deviation scores for matrix x

x = X - 11'X(1/n)



1 is an n x 1 column vector of ones

x is an n x k matrix of deviation: x11,x12,... xnk

X is an n x k matrix of raw score: X11,X12,...Xnk



Compute x'x the k x k deviation sums of squares and cross products matrix for x



Divide each term in the deviation sums od squares and cross product matrix by n to create the variance-covariance matrix. 

   V = x'x(1/n)

        

  V is a k x k variance-covariance matrix

  x'x is the deviation sums od squares and cross product matrix

  n is the number of scores in each column of the original matrix X