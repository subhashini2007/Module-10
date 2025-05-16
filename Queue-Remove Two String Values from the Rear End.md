![image](https://github.com/user-attachments/assets/de8f4f8f-80e4-46c2-a20b-5c2dafbc5b39)# Queue-Remove Two String Values from the Rear End in Python 🧵

This Python program demonstrates how to manage a list of strings and remove the last two elements (i.e., from the rear of the list).

## 🎯 Aim

To write a Python program to:
- Accept `n` string values from the user
- Remove the last two values (rear end of the list)
- Display the updated list

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` from the user (number of strings).
3. Loop `n` times:
   - Read a string input.
   - Append it to the list `q`.
4. Remove the last element using `pop()`.
5. Remove the next last element using `pop()` again.
6. Display the updated list.

##  Program:
```
import queue
de=[]
n=int(input())
for i in range(n):
    de.append(int(input()))
for i in range(3):
    de.pop()
print(de)
```


### Output:
![image](https://github.com/user-attachments/assets/ec15b30b-ece1-453c-87fa-f3e731eaab8e)


## Result:
