# linear-algebra-projects
This repository contains projects of linear algebra. The links are given below:

### Fitting the distribution of heights data
In this worksheet we will implement the steepest descent algorithm on the least squares fitting problem for modelling the distribution of heights in a population with a Gaussian.

We should notice that despite taking input from a vector of data points, it isn't significantly more complicated than when we did steepest descent in the sandpit.
Link: https://github.com/nabilatajrin/linear-algebra-projects/blob/main/FittingTheDistributionOfHeightsData.ipynb

### Gradient descent in a sandpit
In this project, we will examine strategies for steepest descent and how effective they are at finding the supervisor's mobile phone. I.e., solving the minimisation problem.
Link: https://github.com/nabilatajrin/linear-algebra-projects/blob/main/GradientDescentInSandpit.ipynb

### Gram-Schmidt-process
The Gram-Schmidt process is a method for constructing an orthonormal  basis of a space that a set of given vectors span. It can also be used  to determine the dimension of that space, which may be different than  the dimension of the vectors themselves or the number of vectors provided to span the space.

This is a program that computes a  Gram-Schmidt basis, and gives the dimension of a span of vectors.<br>
Link: https://github.com/nabilatajrin/linear-algebra-projects/blob/main/GramSchmidtProcess.ipynb

### Identifying special matrices
When coding or solving data analysis problems, one problem that can  occur is if our code encounters a special matrix that isn't invertible, or has an infinite number of eigenvectors, or similar. On other occasions, for example where we are reducing dimensionality, that might  even be desirable!  So here we will write a code fragment that traps for different types of special matrices before calling the python inversion routine, and classifies the type of special case encountered.  As much as anything, this is to give us a chance to give a Python coding exercise a try out in order to build confidence before doing some longer examples  later.<br>

In this assignment, we shall write a function that will test if a 4×4 matrix is singular, i.e. to determine if an inverse exists, before calculating it.
We shall use the method of converting a matrix to echelon form, and testing if this fails by leaving zeros that can’t be removed on the leading diagonal.<br>
Link: https://github.com/nabilatajrin/linear-algebra-projects/blob/main/IdentifyingSpecialMatrices.ipynb

### page-rank
In this notebook, we'll build on our knowledge of eigenvectors and eigenvalues by exploring the PageRank algorithm.
The notebook is in two parts, the first is a worksheet to get us up to speed with how the algorithm works - here we will look at a micro-internet with fewer than 10 websites and see what it does and what can go wrong.
The second is an assessment which will test our application of eigentheory to this problem by writing code and calculating the page rank of a large network representing a sub-section of the internet.<br>
Link: https://github.com/nabilatajrin/linear-algebra-projects/blob/main/PageRank.ipynb

### reflecting-bear
In this assessment, we will use the knowledge of changing basis to construct a matrix that performs a transformation that is easy in a particular basis, but complicated in our starting basis. Namely we shall help Panda Bear determine what his reflection will look like in a mirror that he has placed at an angle.<br>
Link: https://github.com/nabilatajrin/linear-algebra-projects/blob/main/ReflectingBear.ipynb
