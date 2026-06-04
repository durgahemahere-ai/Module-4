# 4d) Exception Handling in Python: Avoiding Index Errors

##  Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

##  Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

##  Program
```lst = [5, 10, 20]

try:
    print(lst[5])  
except IndexError:
    msg = "You're out of list range"

print(msg)
```

## Output

<img width="807" height="159" alt="image" src="https://github.com/user-attachments/assets/581a988c-28ae-49f2-9893-464cd2c77f0c" />

## Result
Program executed Successfully.
