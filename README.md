mpmath_eigen_markov
===================

Routines for stochastic matrices,
based on [mpmath](https://github.com/fredrik-johansson/mpmath)

Compute the stochastic eigenvector (or stationary distribution vector)
of an irreducible stochastic (or Markov) matrix,
by using the Grassmann-Taksar-Heyman (GTH) algorithm,
a numerically stable variant of Gaussian elimination.

* [Source code](eigen_markov.py)
* [Illustration 1](http://nbviewer.ipython.org/github/oyamad/mpmath_eigen_markov/blob/master/mpmath_eigen_markov_demo01.ipynb):
  Basic usage and comparison with `mpmath.eig`
* [Illustration 2](http://nbviewer.ipython.org/github/oyamad/mpmath_eigen_markov/blob/master/mpmath_eigen_markov_demo02.ipynb):
  `mp` versus `fp`
* [Illustration 3](http://nbviewer.ipython.org/github/oyamad/mpmath_eigen_markov/blob/master/mpmath_eigen_markov_demo03.ipynb):
  Comparison with `numpy.linalg.eig` and `scipy.linalg.eig`
* [pytest](http://nbviewer.ipython.org/github/oyamad/mpmath_eigen_markov/blob/master/pytest_mpmath_eigen_markov.ipynb)
