# Module 6: File Handling

## Overview
File handling allows you to read from and write to files. This is very useful for working with data in Python.

---

## Writing to a File

```python
f = open("file.txt", "w")
f.write("Hello")
f.close()
```

👉 This creates a file named `file.txt` and writes "Hello" into it.

---

## Reading a File

```python
f = open("file.txt", "r")
print(f.read())
f.close()
```

---

## Using with (Recommended)

```python
with open("file.txt", "r") as f:
    print(f.read())
```

👉 Automatically closes the file.

---

## Writing Multiple Lines

```python
with open("file.txt", "w") as f:
    f.write("Line 1\n")
    f.write("Line 2\n")
```

---

## Reading Line by Line

```python
with open("file.txt", "r") as f:
    for line in f:
        print(line.strip())
```

---

## Practice

```python
with open("test.txt", "w") as f:
    f.write("Python file")

with open("test.txt", "r") as f:
    print(f.read())
```

---

## Summary

| Mode | Description |
|------|------------|
| "r" | Read file |
| "w" | Write file |
| open() | Open file |
| read() | Read content |
| write() | Write content |
