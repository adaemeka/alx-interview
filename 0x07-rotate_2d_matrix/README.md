Transpose of a matrix is a task we all can perform very easily in Python (Using a nested loop).
But there are some interesting ways to do the same in a single line.
In Python, we can implement a matrix as a nested list (a list inside a list).
Each element is treated as a row of the matrix.

For example m = [[1, 2], [4, 5], [3, 6]] represents a matrix of 3 rows and 2 columns.
The first element of the list – m[0] and the element in the first row, first column – m[0][0].

Example

Input: [[1,2],[3,4],[5,6]]
Output: [[1,3,5],[2,4,6]]

Explanation: Suppose we are given a matrix
                       [[1, 2],
                        [3, 4],
                        [5, 6]]
Then the transpose of the given matrix will be,
                       [[1, 3, 5],
                        [2, 4, 6]]

Python Programs to Transpose a Matrix in Single Line
There are various approaches to find the Transpose of a matrix in a single line in Python.
Using List Comprehension
Using zip
Using NumPy
Using itertools
