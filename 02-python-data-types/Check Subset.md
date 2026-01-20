# 🔍 Check Subset Using Sets

This program checks whether **set A is a subset of set B** using Python’s built-in set operations.

---

## 📌 Problem Statement

Given two sets of integers:
- Determine whether **all elements of set A are present in set B**

Return:
- `True` → if A is a subset of B  
- `False` → otherwise

---

## 🧠 Approach

Python provides a built-in method:
- `issubset()` → checks subset relation efficiently

✔ Clean  
✔ Optimized  
✔ Readable  

---

## 💻 Code 

```python
a = set(list(map(int, input().split())))
b = set(list(map(int, input().split())))

########### Write your code below ###############
res = a.issubset(b)
########### Write your code above ###############

# Print True or False
print(res)
