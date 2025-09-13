# fibonacci.ipynb

The Fibonacci sequence is a pretty famous sequence of integer numbers. The sequence comes up naturally in many problems and has a nice recursive definition. Learning how to generate it is an essential step in the pragmatic programmer’s journey toward mastering recursion.

To print the Fibonacci sequence in Python, we need to generate a series of numbers where each number is the sum of the two preceding ones, starting from 0 and 1. The Fibonacci sequence follows a specific pattern that begins with 0 and 1, and every subsequent number is the sum of the two previous numbers.

Mathematically, the Fibonacci sequence can be represented as: <br>
F(n) = F(n-1) + F(n-2)<br>

Where:<br>
F(0) = 0<br>
F(1) = 1<br>
F(n) for n > 1 is the sum of the two preceding numbers<br>

The sequence looks like this: 
0, 1, 1, 2, 3, 5, 8, 13, 21, 34, ...
