## 1. Study https://www.udemy.com/course/competitive-programming-algorithms-coding-minutes/learn/lecture/29516057#overview
## 2. Solve https://leetcode.com/problems/palindrome-number/
## 3. Solve https://leetcode.com/problems/two-sum/
## 4. Investigate below
Here are some questions that require analyzing the time and space complexity of multiple code blocks:

### Question 1: Time Complexity Analysis
Consider the following code blocks:

```python
# Code Block A
def function_A(n):
    for i in range(n):
        for j in range(n):
            print(i, j)
```

```python
# Code Block B
def function_B(n):
    for i in range(n):
        for j in range(i):
            print(i, j)
```

```python
# Code Block C
def function_C(n):
    for i in range(n):
        print(i)
    for j in range(n):
        print(j)
```

**Question:**  
- Analyze the time complexity of each code block. What is the overall time complexity of each function (A, B, C)?
- Which function has the highest time complexity?

---

### Question 2: Space Complexity Analysis
Consider the following code blocks:

```python
# Code Block A
def function_A(n):
    arr = []
    for i in range(n):
        arr.append(i)
    return arr
```

```python
# Code Block B
def function_B(n):
    matrix = []
    for i in range(n):
        row = []
        for j in range(n):
            row.append(i * j)
        matrix.append(row)
    return matrix
```

```python
# Code Block C
def function_C(n):
    count = 0
    for i in range(n):
        count += i
    return count
```

**Question:**  
- Analyze the space complexity of each code block. What is the overall space complexity of each function (A, B, C)?
- Which function uses the most memory?

---

### Question 3: Combined Time and Space Complexity Analysis
Consider the following code blocks:

```python
# Code Block A
def function_A(n):
    arr = [0] * n
    for i in range(n):
        for j in range(i, n):
            arr[j] += 1
    return arr
```

```python
# Code Block B
def function_B(n):
    result = 0
    for i in range(n):
        for j in range(n):
            result += i * j
    return result
```

```python
# Code Block C
def function_C(n):
    arr = [0] * n
    for i in range(n):
        arr[i] = sum(range(i))
    return arr
```

**Question:**  
- Determine both the time complexity and space complexity of each function (A, B, C).
- Which function is the most efficient in terms of time and space usage?

---

### Question 4: Nested Functions Complexity Analysis
Consider the following code blocks:

```python
# Code Block A
def helper_A(n):
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result

def function_A(n):
    return helper_A(n)
```

```python
# Code Block B
def helper_B(n):
    arr = []
    for i in range(n):
        arr.append(i ** 2)
    return arr

def function_B(n):
    return helper_B(n)
```

```python
# Code Block C
def helper_C(n):
    count = 0
    while n > 0:
        count += 1
        n //= 2
    return count

def function_C(n):
    return helper_C(n)
```

**Question:**  
- Analyze the time and space complexity of each `helper` function (A, B, C) and how it affects the overall complexity of the main functions (`function_A`, `function_B`, `function_C`).
- Which function pair (`function_X` with its corresponding `helper_X`) is the most efficient in terms of time and space complexity?

---

### Question 5: Recursive Functions Complexity Analysis
Consider the following recursive functions:

```python
# Code Block A
def function_A(n):
    if n == 0:
        return 1
    return n * function_A(n - 1)
```

```python
# Code Block B
def function_B(n):
    if n <= 1:
        return n
    return function_B(n - 1) + function_B(n - 2)
```

```python
# Code Block C
def function_C(n):
    if n <= 1:
        return 1
    return function_C(n // 2) + function_C(n // 2)
```

**Question:**  
- Analyze the time complexity of each recursive function.
- What is the space complexity of each function?
- How does the recursive nature of these functions affect their performance?

---

These questions cover various scenarios involving loops, recursion, nested functions, and data structures, which should help in understanding both time and space complexities in different contexts.

## 5. Create A very basic beautiful Introduction page of yourself using HTML, CSS and Javascript something similar to https://agaraman0.github.io/
