Pascal-Rows
===========

Calculates a requested row of Pascal's Triangle.

===========

Code Description:
The code calculates and prints any desired row of Pascal's Triangle.

Once given a row to calculate, the a vector "line" is created which will store the desired line of Pascal's triangle.
A while loop is used to add values in order to this "line" list by using an (n choose k) equation based on the 
row and index number.

At the end, the row the user wanted is printed out.

Type errors are raised when the row inputed is not positive, or is not an integer. 

Examples are provided below.

===========

Example output for row #3:

  Row #3 in Pascal's triangle is [1, 2, 1].

Example output for row #9:

  Row #9 in Pascal's triangle is [1, 8, 28, 56, 70, 56, 28, 8, 1].

Example output for row #5.2:

  TypeError: Row must be an integer.

Example output for row #-6:

  TypeError: Row must be a positive integer.
  
============
  


