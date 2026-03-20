🔢 NumPy Basics Notebook

This project is a beginner-friendly introduction to NumPy, the core library for numerical computing in Python.

🚀 What is NumPy?

NumPy (Numerical Python) is a library used for:

Fast mathematical operations

Working with arrays and matrices

Scientific computing

Data analysis

It is much faster than Python lists because it uses optimized C code internally.

⚙️ Installation
pip install numpy
📥 Importing NumPy
import numpy as np
🧱 What is an Array?

An array is a collection of elements stored in a single variable.

Example:

arr = np.array([1, 2, 3, 4, 5])
🛠️ Creating Arrays
np.array([1, 2, 3])          # 1D array
np.array([[1, 2], [3, 4]])   # 2D array

np.zeros((2, 2))             # Array of zeros
np.ones((3, 3))              # Array of ones
np.arange(0, 10, 2)          # Range array
np.linspace(0, 1, 5)         # Equal intervals
🔍 Array Properties
arr.shape     # Dimensions
arr.ndim      # Number of dimensions
arr.dtype     # Data type
arr.size      # Total elements
✏️ Array Operations
arr + 2       # Add
arr * 2       # Multiply
arr.mean()    # Average
arr.sum()     # Sum
arr.max()     # Maximum
arr.min()     # Minimum
🔄 Indexing & Slicing
arr[0]        # First element
arr[1:4]      # Slice

For 2D arrays:

arr[0, 1]     # Row 0, Column 1
📈 Key Topics Covered

Creating arrays

Array properties

Mathematical operations

Indexing and slicing

Built-in NumPy functions

🎯 Purpose

This notebook is designed for:

Beginners learning Python

Students starting Data Science

Understanding fast numerical computation

🧠 Future Improvements

You can extend this notebook by adding:

Matrix operations

Linear algebra

Random number generation

Integration with Pandas

🙌 Author

Created by Manik 🚀
