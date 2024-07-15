
# NumPy library



NumPy:
NumPy is a numerical computing library used for high-performance numeric computations. In Python, numeric processing can be slow for large datasets, but NumPy provides optimized functions to handle these tasks efficiently.

Array Creation:

NumPy arrays, known as ndarray, are similar to Python sequences such as lists and tuples. These sequences are collections of items stored at contiguous memory locations. We can create an array using the array() function. The main difference between a list and an array is that arrays take up less memory and are more efficient for numerical operations. The reason why NumPy arrays are more efficient is due to the homogeneity of their objects containing only one data type, while Python lists can contain a mixture of data types. All the items stored in an array can be accessed by index.

NumPy Matrices:

NumPy matrices are strictly 2-dimensional, while NumPy arrays can be N-dimensional. Matrix objects are a subclass of ndarray, so they inherit all the attributes and methods of ndarray. The main advantage of NumPy matrices is that they provide a convenient notation for matrix multiplication: if a and b are matrices, then a * b is their matrix product.

The main advantage of NumPy arrays is that they are more general than 2-dimensional matrices. If you need a 3-dimensional array, you must use an ndarray, not a matrix object. Mixing matrix objects and ndarray in your code can make it difficult to keep track of what type of object your variables are and may result in unexpected behavior during operations like multiplication.

About the project: 

The exercises done in this project are from FreeCodeCamp. 

For more info visit: 
[Numpy](https://numpy.org/doc/stable/user/basics.creation.html)

[Numpy Matrix](https://numpy.org/doc/stable/reference/generated/numpy.matrix.html)

[Numpy Indexing](https://www.geeksforgeeks.org/how-exactly-does-indexing-works-in-arrays/)

[Numpy mask](https://numpy.org/doc/stable/reference/maskedarray.generic.html)


[Free CodeCamp](https://www.freecodecamp.org)
