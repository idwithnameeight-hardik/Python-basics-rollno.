# Python-basics-rollno.
FACTORIAL PROGRAM:
num = int(input("Enter a number: "))

factorial = 1

for i in range(1, num + 1):
    factorial *= i

print("Factorial of", num, "is", factorial)


FIBONACCI SERIES:
n = int(input("Enter the number of terms: "))

a = 0
b = 1

print("Fibonacci Series:")

for i in range(n):
    print(a, end=" ")
    a, b = b, a + b

    STRUCT PROGRAM:
    class Student:
    def __init__(self, name, age, marks):
        self.name = name
        self.age = age
        self.marks = marks

student = Student("Rahul", 20, 85)

print("Student Name:", student.name)
print("Age:", student.age)
print("Marks:", student.marks)




CHANGE/COMMIT by AI:

# Python Programs

This repository contains three basic Python programs for beginners:

## 1. Factorial Program

The factorial program calculates the factorial of a given number using a `for` loop.

**Example:**
`5! = 5 × 4 × 3 × 2 × 1 = 120`

```python
num = int(input("Enter a number: "))

factorial = 1

for i in range(1, num + 1):
    factorial *= i

print("Factorial of", num, "is", factorial)
```

## 2. Fibonacci Program

The Fibonacci program generates a Fibonacci series for the number of terms entered by the user.

```python
n = int(input("Enter the number of terms: "))

a = 0
b = 1

print("Fibonacci Series:")

for i in range(n):
    print(a, end=" ")
    a, b = b, a + b
```

## 3. Structure Program

Python does not have a C-style `struct`. A class can be used to represent structured data. This example stores and displays student information.

```python
class Student:
    def __init__(self, name, age, marks):
        self.name = name
        self.age = age
        self.marks = marks

student = Student("Rahul", 20, 85)

print("Student Name:", student.name)
print("Age:", student.age)
print("Marks:", student.marks)
```

## Programs Included

* Factorial of a number
* Fibonacci series
* Student structure using a Python class

These programs are useful for practicing **loops, variables, input/output, and basic object-oriented programming in Python**. 
