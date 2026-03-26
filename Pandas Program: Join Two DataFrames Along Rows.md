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

Add code here
```
import pandas as pd
dict1 = eval(input())
dict2 = eval(input())
df1 = pd.DataFrame(dict1)
df2 = pd.DataFrame(dict2)
print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)
joined_df = pd.concat([df1, df2], axis=0)

print("\nJoin the said two dataframes along rows:")
print(joined_df)
```
## Output
<img width="1119" height="676" alt="image" src="https://github.com/user-attachments/assets/d622672c-2286-4f59-8f50-3c3b64a02d36" />
<img width="813" height="773" alt="image" src="https://github.com/user-attachments/assets/985953ad-e9de-4874-a6a0-b9e385f0e13a" />

## Result

Thus , the program has been executed succesfully.
