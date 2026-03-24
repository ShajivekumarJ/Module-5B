# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
~~~
# Program to replace second column in a 2D array

import numpy as np

# Input size
rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

# Input array
print("Enter elements row-wise:")
data = []
for i in range(rows):
    row = list(map(int, input().split()))
    data.append(row)

arr = np.array(data)

# Input new column
print("Enter new column values:")
new_col = list(map(int, input().split()))

# Delete second column (index 1)
arr_deleted = np.delete(arr, 1, axis=1)

# Insert new column at index 1
updated_arr = np.insert(arr_deleted, 1, new_col, axis=1)

# Output
print("Updated Array:")
print(updated_arr)
~~~
## Output
<img width="437" height="495" alt="Screenshot 2026-03-24 144047" src="https://github.com/user-attachments/assets/320e2f24-6e22-426d-85ea-c2a5e93d47a9" />

## Result
Thus, the Python program using NumPy to replace the second column in a 2D array was successfully executed and verified.
