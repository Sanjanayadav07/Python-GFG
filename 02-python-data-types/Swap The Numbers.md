# 🔁 Swap Two Numbers

## 📌 Problem Statement
Given two integers `a` and `b`, swap their values.

---

## 🧠 Approach
Use a **temporary variable** to store one value while swapping.

---

## 💻 Code

```python
a = int(input())
b = int(input())

# Swap using temporary variable
temp = a
a = b
b = temp

print(a, b)
