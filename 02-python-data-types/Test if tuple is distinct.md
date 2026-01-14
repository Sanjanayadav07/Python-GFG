# 🔍 Check If All Elements in a Tuple Are Unique 

## 📌 Problem Statement
Given a tuple of integers, check whether **all elements are different**.

- Print `"True"` if all elements are unique  
- Otherwise, print `"False"`

---

## 🧠 Approach
- Convert the tuple to a **set**
- Since sets store only unique elements:
  - If `len(tuple) == len(set)` → all elements are unique

---

## 💻 Code

```python
# User function Template for python3
arr = tuple(map(int, input().split()))

# Check if all elements are different
if len(arr) == len(set(arr)):
    print("True")
else:
    print("False")
