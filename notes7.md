# Module 7: Command Line Arguments (sys.argv)

## Overview
Sometimes we want to pass input to a Python script from the command line. The `sys.argv` list allows us to access these inputs.

---

## Import sys Module

```python
import sys
```

---

## Understanding sys.argv

- `sys.argv` is a list  
- It stores command line arguments  
- `sys.argv[0]` → script name  
- `sys.argv[1]` → first argument  

---

## Example Script

```python
import sys

print(sys.argv)
```

---

## Run Script

```bash
python script.py hello world
```

Output:

```
['script.py', 'hello', 'world']
```

---

## Access Arguments

```python
import sys

print("Script name:", sys.argv[0])
print("First argument:", sys.argv[1])
```

---

## Example: Add Numbers

```python
import sys

a = int(sys.argv[1])
b = int(sys.argv[2])

print(a + b)
```

Run:

```bash
python script.py 5 10
```

Output:

```
15
```

---

## Important Note

- Always provide required arguments  
- Otherwise, Python will show an error  

---

## Practice

```python
import sys

name = sys.argv[1]
print("Hello", name)
```

Run:

```bash
python script.py Hemant
```

---

## Summary

| Concept | Description |
|--------|------------|
| sys.argv | List of arguments |
| argv[0] | Script name |
| argv[1] | First argument |
| import sys | Required to use argv |
