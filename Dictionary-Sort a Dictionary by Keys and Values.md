# 4c)  Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

##  Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

##  Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## Program
```
d=eval(input())
sor=sorted(d.items())
print("Keys and Values sorted in alphabetical order by the key")
for key,value in sor:
    print(f"({key}, {value})",end=" ")
```

## Sample Output

<img width="1082" height="182" alt="image" src="https://github.com/user-attachments/assets/eba30608-1979-443c-9c3f-7dd5abcbe057" />

## Result
Program executed Successfully.
