# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```c
text = input("Enter a string: ")
is_palindrome = True
length = 0
for _ in text:
    length += 1
for i in range(length // 2):
    if text[i] != text[length - i - 1]:
        is_palindrome = False
        break
if is_palindrome:
    print(text, "is a Palindrome.")
else:
    print(text, "is NOT a Palindrome.")

```

## Output
<img width="296" height="67" alt="image" src="https://github.com/user-attachments/assets/b54c3834-d410-46e3-97ce-4ae38aea02e3" />
## Result


## Result
Thus, the program has been executed successfully.
