## 🔗 Logical Operators in Python (and / or / not)

### 📌 Problem Statement
You are given two integers `a` and `b`.  
Apply Python **logical operators** and print the results:

1. `a and b`
2. `a or b`
3. `not a`

Print all outputs in a **single line**, space-separated.

---

### ⏱ Time & Space Complexity
- **Time Complexity:** `O(1)`
- **Space Complexity:** `O(1)`

---

### 💻 Code
```python
a = int(input())
b = int(input())

# Perform logical AND
p = a and b

# Perform logical OR
q = a or b

# Perform logical NOT
r = not a

# Output
print(p, q, r)
