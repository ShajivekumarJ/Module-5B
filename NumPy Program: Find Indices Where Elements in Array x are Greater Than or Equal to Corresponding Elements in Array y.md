# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
~~~
# Program to find indices where x >= y

import numpy as np

# Define arrays
x = np.array([1, 3, 5, 7, 9])
y = np.array([2, 3, 4, 8, 9])

# Find indices
indices = np.where(x >= y)

# Output
print("Array x:", x)
print("Array y:", y)
print("Indices where x >= y:", indices)
~~~
## Output
<img width="543" height="232" alt="Screenshot 2026-03-24 143544" src="https://github.com/user-attachments/assets/643140a7-f79d-4cd8-a926-b0d0f3fe2baa" />

## Result
Thus, the Python program using NumPy to find indices where elements of array x are greater than or equal to elements of array y was successfully executed and verified.
