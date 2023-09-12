# Python NumPy
NumPy is a general-purpose array processing package which provides tools for handling the n-dimensional arrays.

#
In Python we have lists that serve the purpose of arrays, but they are slow to process.
NumPy aims to provide an array object that is up to 50x faster than traditional Python lists.
The array object in NumPy is called <b>ndarray</b>, it provides a lot of supporting functions that make working with ndarray very easy.

#
NumPy’s main object is the homogeneous multidimensional array.
It is a table of elements, all of the same type, indexed by a tuple of positive integers.
<b>In NumPy, dimensions are called axes. The number of axes is rank.</b>
An array can have any number of dimensions. When the array is created, you can define the number of dimensions by using the <b>ndmin</b> argument.

<p>
For example, the array for the coordinates of a point in 3D space, [1, 2, 1], has one axis. That axis has 3 elements in it, so we say it has a length of 3. 

In the example below, the array has 2 axes. The first axis has a length of 2, the second axis has a length of 3.

[[1., 0., 0.],
 [0., 1., 2.]]
</p>

# NumPy Creating Arrays
We can create a NumPy ndarray object by using the <b>array() function</b>

# Access Array Elements
We can access an array element by referring to its index number. The indexes in NumPy arrays start with 0.</br>
To access elements from n-D arrays we can use comma separated integers representing the dimension and the index of the element.
Think of n-D arrays like a table with rows and columns, where the dimension represents the row and the index represents the column.</br>
Use negative indexing to access an array from the <b>end</b>.
