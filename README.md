# All the necessary information to get started with numpys!
# About <h1>
* NumPy stands for numerical Python. It's the backbone of all kinds of scientific and numerical computing in Python.
* numPy is a Linear Algebra Library
  * Very fast as it has bindings to C libraries(Locality Of Reference)
* Used to work with 1D(Vectors) or 2D(Matrices) arrays!
 
Key terms:

- Array - A list of numbers, can be multi-dimensional.
- Scalar - A single number (e.g. 7).
- Vector - A list of numbers with 1-dimesion (e.g. np.array([1, 2, 3])).
- Matrix - A (usually) multi-deminsional list of numbers (e.g. np.array([[1, 2, 3], [4, 5, 6]])).

NumPy uses pseudo-random numbers, which means, the numbers look random but aren't really, they're predetermined.<br />
For consistency, you might want to keep the random numbers you generate similar throughout experiments.<br /> 
To do this, you can use np.random.seed().<br /> 
What this does is it tells NumPy, "Hey, I want you to create random numbers but keep them aligned with the seed."<br /> 
