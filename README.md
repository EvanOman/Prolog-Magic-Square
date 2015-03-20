# Prolog-Magic-Square
A really simple prolog program for finding 3x3 magic squares.

Problem description:

Consider the following 3 × 3 puzzle. The puzzle consists of a 3 × 3 grid whose squares have to be
filled with digits from 1 through 9. The squares have to be filled in such a way that the sum of
numbers along each row, each column, and each of the two major diagonals is 15. Digits are not
to be repeated. An example solution is shown below:

8 3 4
1 5 9
6 7 2

Write a Prolog program to solve the puzzle. Your query will be of the form:
?- solve3x3( [A1, A2, A3, B1, B2, B3, C1, C2, C3] ).
where A1, A2, A3 correspond to values in the 3 squares in the first row, B1, B2, B3 to the values
in the 3 squares in the second row, and C1, C2, C3 to the values in the 3 squares in the last row.
The above query will produce (for one of the solutions shown above):
A1=8, A2=3, A3=4, B1=1, B2=5, B3=9, C1=6, C2=7, C3=2.
