# Module 4: Conditions

## Overview
Conditions are used to make decisions in a program. Python uses `if`, `else`, and `elif` statements for decision making.

---

## if Statement

```python
x = 10

if x > 5:
    print("x is greater than 5")
```

---

## if-else Statement

```python
x = 3

if x > 5:
    print("Greater")
else:
    print("Smaller")
```

---

## if-elif-else Statement

```python
x = 5

if x > 5:
    print("Greater")
elif x == 5:
    print("Equal")
else:
    print("Smaller")
```

---

## Comparison Operators

```python
a = 10
b = 5

print(a > b)   # Greater than
print(a < b)   # Less than
print(a == b)  # Equal
print(a != b)  # Not equal
```

---

## Practice

```python
num = 7

if num > 5:
    print("Number is greater than 5")
else:
    print("Number is 5 or less")
```

---

## Summary

| Operator | Description |
|---------|------------|
| > | Greater than |
| < | Less than |
| == | Equal to |
| != | Not equal to |
| if | Condition check |
| else | Alternative block |
| elif | Multiple conditions |
