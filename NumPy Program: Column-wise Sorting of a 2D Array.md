# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np

arr = np.array([[9, 3, 7],
                [4, 8, 2],
                [6, 1, 5]])

sorted_arr = np.sort(arr, axis=0)

print("Original Array:")
print(arr)

print("Column-wise Sorted Array:")
print(sorted_arr)
```

## Output
<img width="372" height="266" alt="image" src="https://github.com/user-attachments/assets/bde280b1-8b20-43f2-bace-788ddc6ad45b" />

## Result
Thus, the NumPy program to sort the elements of a 2D array column-wise in ascending order using np.sort() with axis=0 was successfully executed, and the desired output was obtained.
