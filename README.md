Title: Matrix Operations

Objective:
• To introduce the basics of Matrices and some of its applications.
• To study the representation, implementation and applications of 2D Array data structures
• To understand the how to pass 2D arrays as parameters to functions.

Problem Statement
Write a python program to compute following computation on matrix:
1. Addition of matrices
2. Subtraction of matrices
3. Multiplication of matrices
4. Transpose of matrix

Problem Definition:
Matrix: A matrix is an m x n rectangular 2-D array of numbers with m rows and n columns.
Or A matrix is an ordered set of numbers listed in rectangular form.

                  Column 0     Column 1     Column 2     Column 3
    row 0         a[0][0]      a[0][1]       a[0][2]      a[0][3]
    row 1         a[1][0]      a[1][1]       a[1][2]      a[1][3]
    row 2         a[2][0]      a[2][1]       a[2][2]      a[2][3]


Initializing Two-Dimensional arrays:
Two-Dimensional arrays may be initialized by providing a list of initial values & it looks like
this:
int A[4][4] ={ {0,1,2,3}, {3,2,1,0}, {3,5,6,1}, {3,8,3,4} };
We might write the two-dimensional array out as:
int A[4][4] = { {0, 1, 2, 3} , {3, 2, 1, 0} , {3, 5, 6, 1} , {3, 8, 3, 4} };
For a two-dimensional array, in order to reference every element, we must use two nested
loops.

Theory:
• 2-Dimentional Array
• Row major and column major storage representation for array
• Address calculation for two dimensional array

Algorithms:
Write down algorithms for following modules:
1. Accepting a Matrix
2. Displaying a Matrix
3. Finding Transpose of matrix
4. Adding two matrices
5. Subtraction of two matrices
6. Multiplication of two matrices

1. Addition of Two Matrices
If A and B are two matrices of same order m x n (to be read as m by n matrix) then their
addition is defined by A + B. For example if A is a matrix of order 2×3 and B is a matrix of
same order 2×3 then addition is possible and the resultant matrix will be of order 2×3. If a
matrix A has its order 2×3 and another matrix B has its order 3×2 then addition is not
possible. So before adding any number of matrices we must check that whether each of the
matrices are of same order or not then we need to proceed further.
