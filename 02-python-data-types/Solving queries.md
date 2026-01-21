# 🔍 Dictionary Query Lookup 

This program maps **integer keys to string values** and retrieves values for given query keys.

---

## 📌 Problem Statement

Given:
- A list of integers `a` (keys)
- A list of strings `b` (values)
- A list of integers `query`

Tasks:
1. Create a dictionary using `a` as keys and `b` as values
2. For each query key:
   - Print its value if present
   - Print `"None"` if the key does not exist

---

## 🧠 Approach

- Use a dictionary to store key–value pairs
- Use `dict.get(key, "None")` for safe lookup
- Store results in a list and print line by line

---

## 💻 Code

```python
a = list(map(int, input().split()))
b = list(map(str, input().split()))
query = list(map(int, input().split()))

dict = {}
for i in range(len(a)):
    dict[a[i]] = b[i]

ans = []
for key in range(len(query)):
    # get value for given key
    val = dict.get(query[key], "None")
    ans.append(val)

# Print ans
print(*ans, sep='\n')
