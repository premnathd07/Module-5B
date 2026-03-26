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
Add code here
```
import pandas as pd
import numpy as np
data = eval(input())
labels=eval(input())
df = pd.DataFrame(data, index=labels)
print(df)
```
## Output
<img width="1130" height="389" alt="image" src="https://github.com/user-attachments/assets/d7843c93-df74-4161-9ce3-4f941dae34c0" />
<img width="1134" height="394" alt="image" src="https://github.com/user-attachments/assets/f02b2d50-a45f-4a05-86e4-9c503ae02218" />
<img width="1134" height="398" alt="image" src="https://github.com/user-attachments/assets/0904b354-dee9-4ac2-92b4-f2ecc43ef9a4" />


## Result
Thus , the program has been executed succesfully.

