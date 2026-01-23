# 🐍 Python String Printing & Separator Demo

This program demonstrates different ways to **print strings in Python** using:
- default printing
- `end` parameter
- `sep` (separator) parameter
- string concatenation

---

## 📌 Problem Statement

Given:
- Two strings `a` and `b`
- A separator character

Print the strings in multiple formats using Python’s `print()` function.

---

## 💻 Code 

```python
# User function Template for python3
a = input()
b = input()
separator = input()[0]

print(a, b)
print(a, b, end='')
print(a, b, sep=separator)
print(a + b)
