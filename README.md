# EXPERIMENT 9 STUDY OF NUMPY IN PYTHON
NIKUNJ DEEP UPADHYAY
25070123081
ENTC B1

#THEORY

Theory: Study of NumPy Library
1. Introduction

NumPy (Numerical Python) is a powerful open-source Python library used for numerical and scientific computing. It provides support for large, multi-dimensional arrays and matrices along with a collection of mathematical functions to operate on these arrays efficiently.



2. NumPy Arrays

The core object of NumPy is the ndarray (N-dimensional array).
Unlike Python lists, NumPy arrays:

Store elements of the same data type

Are faster and more memory-efficient

Support vectorized operations (operations on entire arrays at once)

Example:

1D Array → [1, 10, 20, 30]

2D Array → [[1,2,3],[4,5,6]]

3. Important Array Attributes

ndim

Returns the number of dimensions (axes) of the array.

1D array → ndim = 1

2D array → ndim = 2

size

Returns the total number of elements in the array.

shape

Returns the dimensions of the array in the form (rows, columns).

Example: (3,3) means 3 rows and 3 columns.

dtype

Returns the data type of elements in the array (int, float, etc.).

4. In-Built Functions in NumPy

NumPy provides many built-in functions to create arrays easily:

zeros()

Creates an array filled with zeros.

Example: np.zeros((2,3)) creates a 2×3 matrix of zeros.

ones()

Creates an array filled with ones.

Example: np.ones((3,3)) creates a 3×3 matrix of ones.

eye()

Creates an identity matrix (diagonal elements are 1, others are 0).

5. Arrangement in array.

Provide a range of array using specific limit(start,end,update).

linspace is used to provide range of array using space.

6. Specific operations on array.

Various operations like mean,median,max,min,sum can be performed on array using np.funcname(array).

7. Advantages of NumPy

Faster computation compared to Python lists

Requires less memory

Supports mathematical and statistical operations

Easy handling of multi-dimensional data

8. Conclusion

The NumPy library is essential for numerical computing in Python. It provides efficient array operations, built-in mathematical functions, and powerful tools for handling large datasets. Understanding array properties like dimension, shape, size, and data type is fundamental for scientific and engineering applications.

If you want, I can also provide the algorithm and conclusion section separately in proper practical file format.

Is this conversation helpful so far?
