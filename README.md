### makeCacheMatrix is a function to create a special "matrix" object that can cache its inverse
### It is a function that returns the list of functions below:
### ->  set            set the value of a matrix
### ->  get            caches the matrix
### ->  setmatrix      gets the inverse of the matrix
### ->  getmatrix      caches the inverse of the matrix
###
### The original matrix has to be entered in a variable like the example below:
###
###      a <- makeCacheMatrix(matrix(c(5,7,9,12,13,15,22,23,25),nrow=3,ncol=3))
###
### Remember that the matrix has always to be a square one (2x2, 3x3, 4x4, etc.)
###
###
### cacheSolve: This function computes the inverse of the special "matrix" returned by makeCacheMatrix above. 
### If the inverse has already been calculated (and the matrix has not changed), then the cachesolve should 
### retrieve the inverse from the cache.
###
### It has to processed on the variable defined above, like :
###
###     cacheSolve (a)
###
###
