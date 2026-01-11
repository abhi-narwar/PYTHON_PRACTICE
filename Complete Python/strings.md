# 📘 Python Strings – Complete Guide (Single README)

This README explains **all important Python String topics** with **clear explanation and examples**.  
Beginner + interview friendly.

---

## 1️⃣ String Creation

A **string** is a sequence of characters written inside quotes.

### Creating strings
```python
s1 = "Hello"
s2 = 'Python'
s3 = """Programming"""

s = ""

num = 100
s = str(num)
print(s)   # "100"

#indexing and slicing

s = "Python"

print(s[0])    # P
print(s[1])    # y
print(s[-1])   # n
print(s[-2])   # o

string[start : end : step]

print(s[0:4])    # Pyth
print(s[2:])     # thon
print(s[:3])     # Pyt
print(s[::-1])   # nohtyP (reverse string)

#string methods

s = "hello world"

print(s.upper())        # HELLO WORLD
print(s.lower())        # hello world
print(s.title())        # Hello World
print(s.capitalize())   # Hello world
print(s.strip())        # remove spaces
print(s.replace("world", "python"))
print(s.split())        # ['hello', 'world']
print(s.find("o"))      # index of 'o'
print(s.count("l"))     # count of 'l'
print(s.startswith("h"))
print(s.endswith("d"))

# string formating
name = "Rahul"
age = 20
print(f"My name is {name} and age is {age}")

print("My name is {} and age is {}".format(name, age))

#escape characters

print("Hello\nWorld")
print("My name is \"Rahul\"")
print("Path is C:\\Users\\Admin")


| Escape | Meaning      |
| ------ | ------------ |
| \n     | New line     |
| \t     | Tab          |
| "      | Double quote |
| '      | Single quote |
| \      | Backslash    |


