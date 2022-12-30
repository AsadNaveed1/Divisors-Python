# Divisors-Python

# Q1: Divisors
Weight: 20%

Last update: 18 Oct, 7am

Write a Python program that will ask the user for two integers a and b such that 0 < a < b. Next, the user will be prompted to enter divisors (one or more). All divisors d should be 0 < d <= band integers. The user should be prompted again until the input is suitable. 

Finally, your program should output a matrix with the following elements.

An M in the upper left corner

The first row, after the M, will contain the divisors in ascending order with repeated elements omitted

The first column after the M will contain all integers from a to b-1 in ascending order

A 1 at row i and column j if the i-th integer is divisible by the j-th divisor, otherwise a 0

Matrix elements should be separated by a space.

You may use any functions/operators for this question.

```

Sample runs:

(We will use more test cases, e.g., 20 test cases, to mark each question. Do consider all input cases.)

a b: 1 16
Divisors: 2 3
M 2 3
1 0 0
2 1 0
3 0 1
4 1 0
5 0 0
6 1 1
7 0 0
8 1 0
9 0 1
10 1 0
11 0 0
12 1 1
13 0 0
14 1 0
15 0 1

a b: 1 1
a b: 16 1
a b: 1 16
Divisors: 2 3
M 2 3
1 0 0
2 1 0
3 0 1
4 1 0
5 0 0
6 1 1
7 0 0
8 1 0
9 0 1
10 1 0
11 0 0
12 1 1
13 0 0
14 1 0
15 0 1

a b: -1 16
a b: 1 -16
a b: -1 -16
a b: 0 0
a b: 0 1
a b: 1 16
Divisors: 2 3
M 2 3
1 0 0
2 1 0
3 0 1
4 1 0
5 0 0
6 1 1
7 0 0
8 1 0
9 0 1
10 1 0
11 0 0
12 1 1
13 0 0
14 1 0
15 0 1

a b: 1 16
Divisors: 2 17
Divisors: 17 2
Divisors: 2 3
M 2 3
1 0 0
2 1 0
3 0 1
4 1 0
5 0 0
6 1 1
7 0 0
8 1 0
9 0 1
10 1 0
11 0 0
12 1 1
13 0 0
14 1 0
15 0 1

a b: 120 140
Divisors: 2 20 3
M 2 3 20
120 1 1 1
121 0 0 0
122 1 0 0
123 0 1 0
124 1 0 0
125 0 0 0
126 1 1 0
127 0 0 0
128 1 0 0
129 0 1 0
130 1 0 0
131 0 0 0
132 1 1 0
133 0 0 0
134 1 0 0
135 0 1 0
136 1 0 0
137 0 0 0
138 1 1 0
139 0 0 0

a b: 1 16
Divisors: 3 2
M 2 3
1 0 0
2 1 0
3 0 1
4 1 0
5 0 0
6 1 1
7 0 0
8 1 0
9 0 1
10 1 0
11 0 0
12 1 1
13 0 0
14 1 0
15 0 1

a b: 1 16
Divisors: 3 2 2 3
M 2 3
1 0 0
2 1 0
3 0 1
4 1 0
5 0 0
6 1 1
7 0 0
8 1 0
9 0 1
10 1 0
11 0 0
12 1 1
13 0 0
14 1 0
15 0 1

a b: 2 7
Divisors: 5 4
M 4 5
2 0 0
3 0 0
4 1 0
5 0 1
6 0 0

a b: 2 7
Divisors: 5
M 5
2 0
3 0
4 0
5 1
6 0

a b: 2 7
Divisors: -5
Divisors: 5
M 5
2 0
3 0
4 0
5 1
6 0

a b: 1 16
Divisors: 3 2 -2
Divisors: -3 2 -2
Divisors: -3 -2 -2
Divisors: 3 2 0
Divisors: 3 2
M 2 3
1 0 0
2 1 0
3 0 1
4 1 0
5 0 0
6 1 1
7 0 0
8 1 0
9 0 1
10 1 0
11 0 0
12 1 1
13 0 0
14 1 0
15 0 1

```
