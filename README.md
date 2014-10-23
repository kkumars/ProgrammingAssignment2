## Programming Assignment 2 : Introduction

###Kamlesh Kumar 
###rprog-008
###kamlesh.isi@gmail.com

The first function, makeCacheMatrix creates a special "Matrix", which is really a list containing a function to
     * set the value of the matrix
     * get the value of the matrix
     * set the value of the inverse
     * get the value of the inverse


The following function calculates the inverse of the special "matrix" created with the above function. However, it
first checks to see if the inverse has already been calculated. If so, it gets the inverse from the cache and skips
the computation. Otherwise, it calculates the inverse of the data and sets the value of the inverse in the cache via
the setinv function.
