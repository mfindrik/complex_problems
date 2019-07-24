# Computational complexity
This repository contains pieces of codes for solving some complex computational problems.

## Introduction

Ever since computers are invented people started using it to solve different types of problems by writing algorithms (programs)
that can efficently produce a solution for a given problem. A classical example are algorithms for sorting an array of numbers
according to their value.

Algorithms can further be analysed in terms of their performance which is essentially time (number of operations) and space they 
take to produce a solution. Most commonly the algorithms are analysed only in terms of time they take using Big-Oh notation (although 
other notations exist as well). Of course, Big-Oh notation takes into account input size to the algorithm in order to determine
number of operations necessary to produce a solution. This means sorting an array of 1000 numbers will take longer than sorting an
array of 10 numbers. Some of the most common function that are used to express number of operations of an algorithm are:
  * log(n) - logarithmic time 
  * n - linear time 
  * n*log(n)
  * n over k - polynomial time (where k is a positive number)
  * exp(n) - exponential time

For computer scientist the most interesting types of problems are the ones which require polynomial or exponential number of operations
in order to be solved. The problems known to be solvedin worst-case with polynomial-time algorithms are also called complexity class
P problems. Example of P class problem is standard multiplication of two digits of size n. Using algorithm learned in school you can 
get the solution in n over 2 steps. Polynomical time algorithms are considered to be "efficent" and solvable by standard computers for
reasobly high number of inputs n.

On the other side, there is also a class of problems called NP class for which it is only possible to check in polynomial time wheather a certain result is indeed a correct solution, but it is not possible to obtain the solution in polynomial time.



