## 🧮 Python Formula Practice Problems

### 📌 Problem Statements
This file contains multiple Python formula problems, covering **arithmetic, AP/GP, sum of N numbers, last digit, and modulo operations**.

---

### 1️⃣ Evaluate Formula
**Formula:** `(a + b) // c + d`

#### 💻 Python Code
```python
class Solution:
    def calculate(self, a: int, b: int, c: int, d: int) -> int:
        return (a + b) // c + d
```
---

### 2️⃣ Nth Term of Arithmetic Progression (AP)
**Formula:** `nth_term = a + (n-1) * d`

#### 💻 Python Code
```python
class Solution:
    def nthTerm(self, a, d, n):
        return a + (n - 1) * d
```
---

### 3️⃣ Nth Term of Geometric Progression (GP)
**Formula:** `nth_term = a * r^(n-1)`

#### 💻 Python Code
```python
a = int(input())
n = int(input())
r = 2
ans = a * (r ** (n-1))
print(ans)
```
---
### 4️⃣ Sum of First N Natural Numbers
**Formula:** `sum = n * (n+1) // 2`

#### 💻 Python Code
```python
def nSum(n):
    ans = n * (n + 1) // 2
    return ans

print(nSum(10))
```
---
### 5️⃣ Last Digit of a Number
**Formula:** `last_digit = abs(n) % 10`

#### 💻 Python Code
```python
class Solution:
    def lastDigit(self, n: int) -> int:
        return abs(n) % 10

sol = Solution()
print(sol.lastDigit(4567))
```
---
### 6️⃣ Day Calculation (Modulo 7)
**Formula:** `(d - n) % 7`

#### 💻 Python Code
```python
class Solution:
    def findAnswer(self, d, n): 
        return (d - n) % 7

sol = Solution()
print(sol.findAnswer(5, 2))
```

