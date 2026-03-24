# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
~~~
# Program to create DataFrame with custom index labels

import pandas as pd
import numpy as np

# Create dictionary
exam_data = {
    'name': ['Anil', 'Bala', 'Charan', 'Divya', 'Esha'],
    'score': [85, 90, 78, 92, 88],
    'attempts': [1, 2, 1, 1, 2],
    'qualify': ['Yes', 'Yes', 'No', 'Yes', 'Yes']
}

# Custom index labels
labels = ['a', 'b', 'c', 'd', 'e']

# Create DataFrame
df = pd.DataFrame(exam_data, index=labels)

# Display DataFrame
print(df)
~~~
## Output
<img width="491" height="334" alt="Screenshot 2026-03-24 144227" src="https://github.com/user-attachments/assets/153c2535-285f-478a-a96c-48debf1d84a2" />

## Result
Thus, the Python program to create and display a Pandas DataFrame with custom index labels was successfully executed and verified.
