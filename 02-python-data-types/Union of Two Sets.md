# 🔗 Union of Two Sets & Count Elements 

This program finds the **union of two sets** and prints the **total number of unique elements**.

---

## 📌 Problem Statement

Given two sets of integers:
- Compute their **union**
- Print the **size of the resulting set**

📍 The union contains **all unique elements** from both sets.

---

## 🧠 Approach

Python provides a built-in method:
- `set.union()` → returns a new set containing all unique elements

This ensures:
- No duplicates
- Clean and efficient solution

---

## 💻 Code 

```python
a = set([int(x) for x in input().strip().split()])
b = set([int(x) for x in input().strip().split()])

########### Write your code below ###############
st = a.union(b)
########### Write your code above ###############

# Printing the size of the set which is the total number of elements in the set.
print(len(st))
