````markdown
# Student Class Example in Python

## Description
This program demonstrates the use of **classes, objects, constructors, and instance variables** in Python.

A class named `Student` is created to store student details like name, USN, mobile number, and address.

---

## Class: `Student`

```python
class Student:
````

* A class is a blueprint used to create objects.
* Here, `Student` is used to create student objects.

---

## Constructor (`__init__`)

```python
def __init__(self, n1, u1, m1, a1):
    self.name = n1
    self.usn = u1
    self.mob = m1
    self.add = a1
```

* The constructor runs automatically when an object is created.
* It initializes the instance variables.

### Instance Variables:

* `name` → Stores student name
* `usn` → Stores student USN
* `mob` → Stores mobile number
* `add` → Stores address

---

## Creating Objects

```python
S1 = Student("Rama", "1VTU001", 1234, "Bang")
S2 = Student("Sita", "1VTU002", 1223, "Bang")
S3 = Student("Ravana", "1VTU003", 1235, "Bang")
```

Three student objects are created:

| Object | Name   | USN     | Mobile | Address |
| ------ | ------ | ------- | ------ | ------- |
| S1     | Rama   | 1VTU001 | 1234   | Bang    |
| S2     | Sita   | 1VTU002 | 1223   | Bang    |
| S3     | Ravana | 1VTU003 | 1235   | Bang    |

---

## Accessing Object Data

```python
print(S1.name)
print(S2.mob)
print(S3.add)
```

The object is used to access its instance variables.

### Output:

```
Rama
1223
Bang
```

---

## Concepts Covered

* Class creation
* Object creation
* Constructor method
* Instance variables
* Accessing object attributes

```
```
