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
