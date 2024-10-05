# NumPy functions

### 1. Array Creation
* numpy.array() – Creates an array.
* numpy.zeros() – Creates an array filled with zeros.
* numpy.ones() – Creates an array filled with ones.
* numpy.empty() – Creates an empty array.
* numpy.arange() – Returns evenly spaced values within a given interval.
* numpy.linspace() – Returns evenly spaced numbers over a specified range.
* numpy.eye() – Creates a 2D array with ones on the diagonal and zeros elsewhere.
  
### 2. Array Manipulation
* numpy.reshape() – Gives a new shape to an array without changing its data.
* numpy.ravel() – Flattens the array.
* numpy.transpose() – Permutes the dimensions of an array.
* numpy.concatenate() – Joins arrays along an existing axis.
* numpy.hstack() – Stacks arrays horizontally.
* numpy.vstack() – Stacks arrays vertically.
* numpy.split() – Splits an array into multiple sub-arrays.
* numpy.resize() – Returns a new array with a specified shape.
  
### 3. Mathematical Operations
* numpy.add() – Element-wise addition of arrays.
* numpy.subtract() – Element-wise subtraction of arrays.
* numpy.multiply() – Element-wise multiplication of arrays.
* numpy.divide() – Element-wise division of arrays.
* numpy.dot() – Dot product of two arrays.
* numpy.power() – Raises each element to a specified power.
* numpy.sqrt() – Element-wise square root.
* numpy.sin(), numpy.cos(), numpy.tan() – Trigonometric functions.
* numpy.exp() – Exponential of all elements in the array.
* numpy.log() – Natural logarithm of elements.

### 4. Statistical Operations
* numpy.mean() – Returns the mean of the array elements.
* numpy.median() – Returns the median of the array elements.
* numpy.std() – Returns the standard deviation of array elements.
* numpy.var() – Returns the variance of array elements.
* numpy.sum() – Returns the sum of array elements.
* numpy.min() – Returns the minimum value of the array.
* numpy.max() – Returns the maximum value of the array.
* numpy.percentile() – Computes the nth percentile of the array.
  
### 5. Indexing and Slicing
* numpy.where() – Returns elements chosen from x or y depending on condition.
* numpy.take() – Takes elements from an array along an axis.
* numpy.put() – Replaces specified elements of an array.
* numpy.argsort() – Returns indices that would sort the array.
* numpy.argmin() – Returns the index of the minimum value.
* numpy.argmax() – Returns the index of the maximum value.
  
### 6. Linear Algebra
* numpy.linalg.inv() – Computes the (multiplicative) inverse of a matrix.
* numpy.linalg.eig() – Computes the eigenvalues and eigenvectors of a matrix.
* numpy.linalg.det() – Computes the determinant of a matrix.
* numpy.linalg.svd() – Singular Value Decomposition.
* numpy.linalg.solve() – Solves a linear matrix equation.

### 7. Random Sampling
* numpy.random.rand() – Generates random numbers in a given shape from a uniform distribution.
* numpy.random.randn() – Generates random numbers from a standard normal distribution.
* numpy.random.randint() – Generates random integers.
* numpy.random.choice() – Randomly selects elements from an array.
* numpy.random.shuffle() – Shuffles the contents of an array.

#  NumPy attributes

### 1. Array Shape and Size
* ndarray.shape – Returns the shape of the array (dimensions).
* ndarray.ndim – Returns the number of dimensions (axes) of the array.
* ndarray.size – Returns the total number of elements in the array.
* ndarray.itemsize – Returns the size (in bytes) of each element in the array.
* ndarray.nbytes – Returns the total number of bytes consumed by the elements of the array.
* ndarray.T – Returns the transpose of the array (for 2D arrays).

### 2. Array Type and Information
* ndarray.dtype – Returns the data type of the array elements.
* ndarray.real – Returns the real part of the array elements (for complex numbers).
* ndarray.imag – Returns the imaginary part of the array elements (for complex numbers).
* ndarray.flags – Returns information about the memory layout of the array.
* ndarray.strides – Returns the tuple of bytes to step in each dimension when traversing an array.

### 3. Array Content
* ndarray.flat – Returns a 1D iterator over the array elements.
* ndarray.base – Returns the base array if the array is a view or a copy; otherwise, it returns None.
