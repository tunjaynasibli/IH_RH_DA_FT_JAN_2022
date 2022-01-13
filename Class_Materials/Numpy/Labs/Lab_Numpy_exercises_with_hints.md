

# numpy exercises

This is a collection of exercises that have been collected in the numpy mailing list, on stack overflow
and in the numpy documentation. The goal of this collection is to offer a quick reference for both old
and new users but also to provide a set of exercises for those who teach.


If you find an error or think you've a better way to solve some of them, feel
free to open an issue at <https://github.com/rougier/numpy-100>.
File automatically generated. See the documentation to update questions/answers/hints programmatically.

#### 1. Import the numpy package under the name `np` (★☆☆)
`hint: import … as`
#### 3. Create a null vector of size 10 (★☆☆)
`hint: np.zeros`

#### 6. Create a null vector of size 10 but the fifth value which is 1 (★☆☆)
`hint: array[4]`
#### 7. Create a vector with values ranging from 10 to 49 (★☆☆)
`hint: arange`
#### 8. Reverse a vector (first element becomes last) (★☆☆)
`hint: array[::-1]`
#### 9. Create a 3x3 matrix with values ranging from 0 to 8 (★☆☆)
`hint: reshape`
#### 10. Find indices of non-zero elements from [1,2,0,0,4,0] (★☆☆)
`hint: np.nonzero`
#### 11. Create a 3x3 identity matrix (★☆☆)
`hint: np.eye`
#### 12. Create a 3x3x3 array with random values (★☆☆)
`hint: np.random.random`
#### 13. Create a 10x10 array with random values and find the minimum and maximum values (★☆☆)
`hint: min, max`
#### 14. Create a random vector of size 30 and find the mean value (★☆☆)
`hint: mean`

#### 17. What is the result of the following expression? (★☆☆)
```python
0 * np.nan
np.nan == np.nan
np.inf > np.nan
np.nan - np.nan
np.nan in set([np.nan])
0.3 == 3 * 0.1
```
`hint: NaN = not a number, inf = infinity`
#### 18. Create a 5x5 matrix with values 1,2,3,4 just below the diagonal (★☆☆)
`hint: np.diag`

#### 22. Normalize a 5x5 random matrix (★☆☆)
`hint: (x -mean)/std`

#### 24. Multiply a 5x3 matrix by a 3x2 matrix (real matrix product) (★☆☆)
`hint:`

#### 26. What is the output of the following script? (★☆☆)
```python
# Author: Jake VanderPlas

print(sum(range(5),-1))
from numpy import *
print(sum(range(5),-1))
```
`hint: np.sum`

#### 30. How to find common values between two arrays? (★☆☆)
`hint: np.intersect1d`

#### 37. Create a 5x5 matrix with row values ranging from 0 to 4 (★★☆)
`hint: np.arange`

#### 40. Create a random vector of size 10 and sort it (★★☆)
`hint: sort`

#### 45. Create random vector of size 10 and replace the maximum value by 0 (★★☆)
`hint: argmax`

#### 58. Subtract the mean of each row of a matrix (★★☆)
`hint: mean(axis=,keepdims=)`
#### 59. How to sort an array by the nth column? (★★☆)
`hint: argsort`

#### 89. How to get the n largest values of an array (★★★)
`hint: np.argsort | np.argpartition`

#### 93. Consider two arrays A and B of shape (8,3) and (2,2). How to find rows of A that contain elements of each row of B regardless of the order of the elements in B? (★★★)
`hint: np.where`
