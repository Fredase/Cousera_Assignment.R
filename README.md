# Cousera_Assignment.R
## create a special "matrix" object that can cache its inverse
## the function will reurn the inverse of a matrix

makeCacheMatrix <- function(x = matrix()){
      p <- NULL
      set <- function(y){
        x <<- y
        p <<- NULL
      }
      
      get <- function(x)
      setmatrix <- function(1/x) p <<- 1 / x
      getInverse <- function() p
      
}

solveCache <- function(x, ...){
  ##returns the inverse of matrix "x"
  return(makeCacheMatrix)
}
