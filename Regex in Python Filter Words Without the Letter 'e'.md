# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```c
import re
text = "We love Python and data science but fun coding is awesome"
words_without_e = re.findall(r'\b[^eE\s]+\b', text)
print("Original text:")
print(text)
print("\nWords without the letter 'e':")
print(words_without_e)

```
## Output
<img width="632" height="120" alt="image" src="https://github.com/user-attachments/assets/44922af5-fc55-49ad-b26e-4c19b9edbcbf" />

## Result
Thus, the program has been executed successfully.

