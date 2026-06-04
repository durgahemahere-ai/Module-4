# 4e) File Handling in Python: Find the longest word in a file.

##  Aim
To Write a function to find the longest word in a file.
##  Algorithm
1.Open the file in read mode.

2.Read the entire content of the file.

3.Split the content into individual words using spaces as separators.

4.Initialize two variables:

max_length = 0 → to store the length of the longest word found so far.

longest_word = "" → to store the longest word itself.

5.For each word in the list of words:

a. Check the length of the word.

b. If the length of the word is greater than max_length:

Update max_length to the length of the current word.

Update longest_word to the current word.

7.Return longest_word as the result.

8.Close the file (automatically handled using with statement).

##  Program
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)
def find_longest_word(file_path):
    with  open(file_path,'r') as file:
        content=file.read().split()
        a=0
        c=""
        for i in content:
            if len(i)>a:
                a=len(i)
                c=i
        return c
```
## Output
<img width="929" height="348" alt="image" src="https://github.com/user-attachments/assets/6cf4854c-547d-4214-925b-7452f300cd98" />

## Result
Program executed Successfully.
