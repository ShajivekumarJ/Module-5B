# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
~~~
# Program to join two DataFrames row-wise

import pandas as pd

# First DataFrame
student_data1 = {
    'name': ['Anil', 'Bala'],
    'marks': [85, 90]
}

df1 = pd.DataFrame(student_data1)

# Second DataFrame
student_data2 = {
    'name': ['Charan', 'Divya'],
    'marks': [78, 92]
}

df2 = pd.DataFrame(student_data2)

# Concatenate DataFrames
df = pd.concat([df1, df2], axis=0)

# Display result
print(df)
~~~
## Output
<img width="411" height="299" alt="Screenshot 2026-03-24 144346" src="https://github.com/user-attachments/assets/315335c6-1a33-439d-bdc3-b95764b7cfbf" />

## Result
Thus, the Python program to join two DataFrames along rows using Pandas was successfully executed and verified.
