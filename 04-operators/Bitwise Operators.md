## 🔢 Bitwise Operators in Python ( ^  &  |  ~ )

### 📌 Problem Statement
You are given three integers `a`, `b`, and `c`.  
Perform the following **bitwise operations**:

1. `a ^ a`
2. `c ^ b`
3. `a & b`
4. `c | (a ^ a)`
5. `~(c ^ b)`

Print the results in a **single line**, space-separated.

---

### ⏱ Time & Space Complexity
- **Time Complexity:** `O(1)`
- **Space Complexity:** `O(1)`

---

### 💻 Code
```python
a = int(input())
b = int(input())
c = int(input())

# a ^ a
d = a ^ a

# c ^ b
e = c ^ b

# a & b
f = a & b

# c | (a ^ a)
g = c | (a ^ a)

# ~e
e = ~e

print(d, e, f, g)
