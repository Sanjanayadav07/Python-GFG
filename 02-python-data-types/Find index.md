# 🔍 Find Index of an Element in a Tuple 

## 📌 Problem Statement
Given:
- A tuple `arr`
- An integer `x`

Print:
- The **index of `x`** in the tuple if it exists
- Otherwise, print `-1`

---

## 🧠 Approach
- Use the `in` operator to check if `x` exists
- If present, use `tuple.index()` to get its index
- Otherwise, print `-1`

---

## 💻 Code

```python
# User function Template for python3

arr = tuple(map(int, input().split()))
x = int(input())

# Print the index of x in arr
if x in arr:
    print(arr.index(x))
else:
    print(-1)
