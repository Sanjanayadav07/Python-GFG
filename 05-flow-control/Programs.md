# 🐍 Python Basics – Conditional & Operators

This file contains **basic Python programs** based on conditions, math operations, and decision making.

---

## 🧮 Program 1: Who Wins (Odd / Even)

📌 If the number is **even → Friend wins**  
📌 If the number is **odd → You win**

```python
n = int(input())

if n % 2 == 0:
    print("Friend")
else:
    print("You")
```
---

# 🔢 Progam 2: Greatest of Three Numbers 

This program takes **three integers** as input and prints the **greatest number** among them.

---

## 💻 Code

```python
a = int(input())
b = int(input())
c = int(input())

print(max(a, b, c))
```
---
# Program 3: ➕➖✖️ Calculator Using Operator Code

This function performs a basic calculation based on the **operator code** provided.

---

## 🧠 Operator Codes
- `1` ➜ Addition ➕  
- `2` ➜ Subtraction ➖  
- `3` ➜ Multiplication ✖️  

---

## 💻 Code

```python
class Solution:
    def calculate(self, a: int, b: int, operator: int) -> None:
        if operator == 1:
            print(a + b, end="")
        elif operator == 2:
            print(a - b, end="")
        elif operator == 3:
            print(a * b, end="")
        else:
            print("Invalid Input", end="")
```
---
# 📅 Program 4: Leap Year Check 

This program checks whether a given year is a **leap year** or not.

---

## 💻 Code

```python
year = int(input())

if (year % 400 == 0) or (year % 4 == 0 and year % 100 != 0):
    print("True")
else:
    print("False")
```
---
