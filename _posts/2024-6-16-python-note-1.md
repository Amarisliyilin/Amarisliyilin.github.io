## Python Study Notes

### 1. Introduction
Python is a widely-used high-level programming language known for its simplicity and readability. It supports various programming paradigms, including object-oriented, procedural, and functional programming.

### 2. Installation and Setup
- **Download Python**: Get the latest version from the [official Python website](https://www.python.org/).
- **Install Python**: Choose the appropriate installer for your operating system (Windows, macOS, Linux).
- **Set Environment Variables**: During installation, select the option to add Python to your system environment variables.

### 3. Basic Syntax
#### 3.1 Comments
```python
# This is a single-line comment

"""
This is a multi-line comment
used for longer explanations
"""
```

#### 3.2 Variables and Data Types
```python
# Variables
name = "Alice"
age = 25

# Data Types
integer = 10        # Integer
floating = 10.5     # Float
string = "Hello"    # String
boolean = True      # Boolean
```

#### 3.3 Control Flow
##### 3.3.1 If Statements
```python
if age > 18:
    print("Adult")
else:
    print("Minor")
```

##### 3.3.2 Loops
```python
# For loop
for i in range(5):
    print(i)

# While loop
count = 0
while count < 5:
    print(count)
    count += 1
```

### 4. Functions
```python
def greet(name):
    return f"Hello, {name}!"

message = greet("Alice")
print(message)
```

### 5. Modules and Packages
- **Importing a Module**: Use the `import` statement to include a module.
```python
import math
print(math.sqrt(16))
```

- **Creating a Module**: Save your Python code in a file with a `.py` extension.
```python
# my_module.py
def add(a, b):
    return a + b
```

- **Using Your Module**:
```python
from my_module import add
result = add(2, 3)
print(result)
```

### 6. File Handling
```python
# Writing to a file
with open('example.txt', 'w') as file:
    file.write("Hello, World!")

# Reading from a file
with open('example.txt', 'r') as file:
    content = file.read()
    print(content)
```

### 7. Exception Handling
```python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
finally:
    print("This will always execute.")
```
