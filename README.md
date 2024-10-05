Print Elements in Sorted Order using Row-Column wise Sorted Matrix in Python
Here, on this page, we will discuss the program to Print Elements in Sorted Order using Row-Column wise Sorted Matrix in Python programming language. We are given a matrix in which each row and column are sorted in a non-decreasing manner.
Print Elements in Sorted Order of 2D Matrix

Algorithm
Let’s say the number of rows is n and the number of columns is m.
Now, create an array of sizes (n*m).
Insert all the elements of the matrix in the declared array.
Using the sort() function sort the entire array.
Print the array.
Time and Space Complexity :
Time-Complexity : O(n*m*log(n*m))
Space-Complexity : O(n*m)
Print Elements in Sorted Order of 2D Matrix in Python
Python Code
Run
Matrix = [[1, 20, 43, 14],
          [50, 69, 17, 81],
          [99, 10, 11, 22],
          [13, 54, 95, 16]]

arr = []
x, n, m = 0, 4, 4

for i in range(n):
    for j in range(m):
        arr.append(Matrix[i][j])

size = n*m
arr.sort()

for i in range(size):
    print(arr[i], end=" ")
Output
1 10 11 13 14 16 17 20 22 43 50 54 69 81 95 99 
