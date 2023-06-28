Pascal’s triangle is the arrangement of the data in triangular form which is used to represent the coefficients of the binomial expansions, i.e. the second row in Pascal’s triangle represents the coefficients in (x+y)2 and so on. In Pascal’s triangle, each number is the sum of the above two numbers. Pascal’s triangle has various applications in probability theory, combinatorics, algebra, and various other branches of mathematics.

What is Pascal’s Triangle?
It is named after the famous Philosopher and Mathematician Balise ‘Pascal’ who developed a pattern of numbers starting with 1 and the numbers beneath are the summation of the above numbers. To start making Pascal’s triangle, first, write down the number 1. The second row is written down by two 1s again. Other rows are generated using the previous rows to make a triangle of numbers. Each row begins and ends with a 1.

A basic structure of the Pascal triangle is shown in the image added below,

https://media.geeksforgeeks.org/wp-content/uploads/20230531151712/Pascal-triangle.PNG

Pascal’s Triangle Definition
We define the Pascal triangle as the basic set of numbers arrange in a triangular array such that each element in Pascal’s triangle is the sum of the two numbers above it. Pascal’s triangle starts with 1  and this was first proposed by the famous French mathematician Balise Pascal and hence named Pascal’s Triangle.

This triangle represents the coefficients of the binomial expansion for various powers. (we have to make sure that the power in the binomial expansion is only a natural number then only Pascal’s triangle represents the coefficients in the binomial expansion)

Pascal’s Triangle Construction
We can easily construct the Pad=scal’s triangle by just adding the two numbers of the above row to get the next number in the row below. We can assume that the zeroth row starts with a single element 1 and then the element in the second row is 1 1 which is formed by adding 1+0 and 1+0. Similarly, the elements in the second row are, 1 2 1 2hich are formed by adding, 1+0, 1+1, and 1+0, and thus the elements in the third row are obtained. Expanding this concept to the nth row we get a Pascal’s Triangle with n+1 rows. 

Pascal’s Triangle upto 3rd row is shown in the image below,

https://media.geeksforgeeks.org/wp-content/uploads/20230531153640/pascal-triangle-3-row.PNG

From the above figure, we easily observe that the first and the last element in each row is 1.

Pascal’s Triangle Formula
Pascal Triangle Formula is the formula that is used to find the number that is to be filled in the mth column and the nth row. As we know that the terms in Pascal’s triangle are the summation of the terms in the above row. So we require the elements in the (n-1)th row, and (m-1)th and nth columns to get the required number in the mth column and the nth row.

The elements of the nth row of Pascal’s triangle are given, nC0, nC1, nC2, …, nCn. 

The formula for finding any number in Pascal’s triangle is:
nCm = n-1Cm-1 + n-1Cm

Where,

nCm represents the (m+1)th element in the nth row., and
n is a non-negative integer [0 ≤ m ≤ n]

We can understand this formula using the example discussed below,

Example: Find the third element in the third row of Pascal’s triangle.

Solution:

We have to find the 3rd element in the 3rd row of Pascal’s triangle.

Pascal Triangle Formula is,

nCk = n-1Ck-1  + n-1Ck

where nCk represent (k+1)th element in nth row.

Thus, 3rd element in the 3rd row is,

3C2 = 2C1 + 2C2

⇒ 3C2 = 2 + 1

⇒ 3C2 = 3

Thus, the third element in the third row of Pascal’s triangle is 3.
