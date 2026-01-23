# 🐍 Python String Repetition & Concatenation

This program demonstrates how to:
- Convert integers to strings
- Repeat strings using `*`
- Concatenate strings and characters

---

## 📌 Problem Statement

You are given:
- An integer `a`
- An integer `b`
- A string/character `c`

Create an output string using the rule:
```
(str(a) repeated a times) + c + (str(b) repeated b times)
```

---

## 💻 Code

```python
# User function Template for python3
a = int(input())
b = int(input())
c = input()

output = str(a) * a + c + str(b) * b
print(output)


