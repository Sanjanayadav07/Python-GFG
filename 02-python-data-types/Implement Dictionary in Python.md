# 📘 Dictionary Operations 

This program demonstrates **basic dictionary operations** in Python:
- Insert a key–value pair
- Delete a key
- Search and print value for a given key

---

## 📌 Problem Statement

Given:
- A list of keys
- A list of values
- A key–value pair to insert
- A key to delete
- A key to search  

Perform the following operations on a dictionary:
1. Insert a new key–value pair
2. Delete a key if it exists
3. Print marks of a given key if present

---

## 🧠 Approach

- Use `dict(zip(keys, values))` to create dictionary
- Insert using `my_dict[key] = value`
- Delete using `del my_dict[key]`
- Search using `in` and `get()` method

---

## 💻 Code 

```python
keys = input().split()
values = map(int, input().split())
my_dict = dict(zip(keys, values))
k, v = input().split()

########### Insert Operation ###########
my_dict[k] = int(v)
print("Inserted")

d = input()

########### Delete Operation ###########
if d in my_dict:
    del my_dict[d]
    print("Deleted")
else:
    print(-1)

p = input()

########### Search Operation ###########
if p in my_dict:
    print(f"Marks of {p} is {my_dict[p]}")
else:
    print(-1)
