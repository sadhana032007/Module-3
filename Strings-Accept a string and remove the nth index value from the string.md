# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
s=input()
n=int(input())
if n<len(s):
    r=s[:n]+s[n+1:]
    print("String after removing character at index {}".format(n))
else:
    print("Index out of range")

```

## Output
<img width="1912" height="532" alt="Screenshot 2025-10-18 233940" src="https://github.com/user-attachments/assets/c1b8d99c-b03a-4c22-8d8e-b7ae4baaccb2" />

## Result
The Strings-Remove Nth Index Character from a String is executed successfully.
