# DA_Assignment3.2
Define matrix mymat by replicating the sequence 1:5 for 4 times and transforming into a matrix, sum over rows and columns.
mymat<-matrix(rep(seq(5), 4), ncol=5)
mymat
apply(mymat, 1, sum)
apply(mymat, 2, sum)
