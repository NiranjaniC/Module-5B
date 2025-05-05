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
```
import numpy as np
x = np.array([0, 2, 4, 5, 6, 7, 8, 9,10, 11])
y = np.array([0, 1, 3, 7, 5, 6, 7, 6, 8, 9])
greater_mask = x > y   
equal_mask = x == y     
greater_indices = np.where(greater_mask)
equal_indices = np.where(equal_mask)
print(greater_indices)
print(equal_indices)
```

## Output

![image](https://github.com/user-attachments/assets/c3a0a53d-7d29-4da4-8df7-842fd9dba753)


## Result
Thus the program has been executed successfully.
