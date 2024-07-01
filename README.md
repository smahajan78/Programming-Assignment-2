X<- matrix(c(1,2,3,4),2,2)

##solve(X)

X1<- makeCacheMatrix(X) 

{cacheSolve(X1)}

##inverse returned after computation

cacheSolve(X1)

## inverse returned from cache

