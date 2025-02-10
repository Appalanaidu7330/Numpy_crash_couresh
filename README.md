Numpy Crash Course
NumPy
NumPy (Numerical Python) is a core package for scientific computing in Python. It provides a high-performance, multidimensional array object, and tools for working with these arrays. With NumPy, you can perform efficient mathematical and logical operations on large datasets, which is essential for data analysis, machine learning, and scientific computations.

Key Concepts in NumPy
1.ndarray (N-dimensional Array)
The primary object in NumPy is the ndarray, a powerful, multidimensional array structure. Unlike Python's built-in list, NumPy arrays are homogeneous (they store elements of the same type) and are optimized for performance. An ndarray is essentially a grid of values indexed by a tuple of non-negative integers.

2.Array Attributes: Arrays in NumPy have several important attributes:
Shape: Defines the dimensions of the array (e.g., for a 2D array, it could be rows and columns).

3.Array Creation: You can create arrays in different ways:
From Lists/Tuples: Directly convert lists or tuples to arrays

4.Array Indexing and Slicing:
Indexing: Access elements using indices. The index is zero-based, meaning it starts at 0.

5.Array Operations:
Element-wise operations: NumPy arrays allow for element-wise mathematical operations, which is much faster than using Python's built-in lists.

Universal Functions (ufuncs): NumPy includes a wide range of mathematical functions (such as np.sqrt(), np.exp(), np.log(), etc.) that operate element-wise on arrays.

6.Broadcasting:
Broadcasting is a powerful feature in NumPy that allows operations on arrays of different shapes and sizes. The smaller array is "broadcast" to the shape of the larger array so they can be operated on together. This avoids the need for explicit loops.

7.Reshaping Arrays:
You can change the shape of an array using the reshape() method. This does not modify the data, only the way it's viewed.

8.Aggregations and Reductions:
NumPy provides a set of functions that allow you to compute summary statistics (e.g., sum, mean, median, etc.) and perform reductions over arrays.

Mean: Calculates the average of elements. python Copy Edit

9.Linear Algebra:
NumPy provides a wide range of linear algebra operations (such as matrix multiplication, determinants, eigenvalues, etc.) via the np.linalg module.

10.Random Module:
NumPy has a random submodule to generate random numbers, shuffle data, and perform random sampling.

11.Masking and Conditional Indexing:
Boolean masking allows you to filter out elements from an array based on conditions.

12.Efficiency:
Memory efficiency: NumPy arrays are more memory-efficient than Python lists. Performance: NumPy operations are typically faster than Python loops because NumPy operations are implemented in C and are optimized for performance.
