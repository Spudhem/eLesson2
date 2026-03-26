# Module 5: Loops

## Overview
Loops are used to repeat a block of code multiple times. Python provides `for` and `while` loops for iteration.

---

## for Loop

### Description
The `for` loop is used to repeat a block of code a fixed number of times.

```python
for i in range(5):
    print(i)
```

Output:

```
0
1
2
3
4
```

---

## Using range()

```python
for i in range(1, 6):
    print(i)
```

Output:

```
1
2
3
4
5
```

---

## while Loop

### Description
The `while` loop runs as long as a condition is true.

```python
i = 0

while i < 5:
    print(i)
    i += 1
```

Output:

```
0
1
2
3
4
```

---

## Loop with Condition

```python
for i in range(5):
    if i == 3:
        print("Found 3")
```

---

## Practice

```python
for i in range(1, 4):
    print(i)
```

---

## Summary

| Concept | Description |
|--------|------------|
| for loop | Repeat fixed times |
| while loop | Repeat until condition |
| range() | Generate numbers |
| i += 1 | Increment value |
