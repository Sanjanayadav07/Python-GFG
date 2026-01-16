# 🧮 Python Set Operations

This program demonstrates basic operations on a **set** in Python:
- Insert an element
- Remove an element
- Display the set in sorted order
- Calculate the sum of elements

---

## 📌 Problem Statement

Given:
- A set of integers
- An integer `i` to insert into the set
- An integer `r` to remove from the set

Perform the following operations:
1. Insert `i` into the set
2. Print the set in sorted order
3. Remove `r` from the set
4. Print the updated set
5. Print the sum of elements in the set

---

## 🧠 Approach

- Use `set.add()` to insert elements
- Use `set.discard()` to safely remove elements
- Use `sorted()` for ordered output
- Use `sum()` to calculate total

---

## 💻 Code 

```python
# User function Template for python3
st = {int(x) for x in input().split()}
i = int(input())
r = int(input())

# Insert i in set
st.add(i)

# Printing the set
for x in sorted(st):
    print(x, end=' ')
print()

# Remove r from set
st.discard(r)

# Printing the set
for x in sorted(st):
    print(x, end=' ')
print()

# Sum of elements in set
total = sum(st)

# Print sum of set
print(total)
