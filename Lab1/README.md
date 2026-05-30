# Lab Report

## Lab Session 1: Working with Python Lists

### Student Information

| Field    | Details                |
| -------- | ---------------------- |
| Name     | Maheshwar Pant         |
| Roll No. | 230322                 |
| Faculty  | Science and Technology |
| Subject  | Machine Learning       |
| Lab No.  | 1                      |
| Date     | 2083-02-12             |

---

# Title

**Working with Python Lists**

---

# Objective

The objectives of this laboratory session are:

1. To understand the concept of Python Lists.
2. To perform basic list operations such as accessing, updating, inserting, and deleting elements.
3. To learn common list methods used in Python.
4. To understand nested lists and matrix representation.
5. To implement matrix operations using lists.
6. To learn list comprehensions for efficient data processing.
7. To understand the role of lists in Machine Learning and data preprocessing.

---

# Theory

## Introduction to Python Lists

A List is one of Python's most commonly used data structures. It is an ordered and mutable collection that can store multiple items of different data types. Lists are represented using square brackets `[]`.

### Features of Lists

* Ordered collection.
* Mutable (modifiable).
* Allows duplicate elements.
* Supports indexing and slicing.
* Can contain mixed data types.

### Example

```python
subjects = ["Mathematics", "Physics", "Chemistry", "Biology", "English"]
```

### Applications of Lists

* Dataset storage.
* Data preprocessing.
* Feature collection.
* Storing training and testing samples.
* Machine Learning data manipulation.

---

## List Methods

Python provides several built-in methods to manipulate lists efficiently.

| Method      | Description                               |
| ----------- | ----------------------------------------- |
| `append()`  | Adds element at the end                   |
| `insert()`  | Inserts an element at a specific position |
| `remove()`  | Removes a specific element                |
| `pop()`     | Removes element by index                  |
| `sort()`    | Sorts elements                            |
| `reverse()` | Reverses list order                       |

---

## Nested Lists

A nested list is a list that contains other lists as its elements. Nested lists are commonly used to represent matrices.

### Example

```python
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
```

---

## List Comprehensions

List comprehensions provide a concise way to create lists.

### Syntax

```python
[new_item for item in iterable]
```

### Example

```python
squares = [x*x for x in range(1, 6)]
print(squares)
```

### Advantages

* Shorter code.
* Better readability.
* Faster execution.
* Useful for data transformation.

---

# Relevance to Machine Learning

Lists are fundamental data structures used in Machine Learning for storing datasets, labels, feature values, and intermediate results. List comprehensions are frequently used during data preprocessing, while nested lists are useful for representing matrices before moving to libraries such as NumPy and Pandas.

---

# Problem Statement / Questions to be Solved

## Experiment 1: Introduction to Python Lists

1. Create a list of five subjects.
2. Print the first and last element.
3. Replace the third subject with another subject.

---

## Experiment 2: List Operations and Methods

1. Create a list of integers.
2. Add two elements using `append()`.
3. Remove one element.
4. Sort the list.
5. Reverse the list.

---

## Experiment 3: Nested Lists and Matrix Operations

1. Create a 3×3 matrix.
2. Print all diagonal elements.
3. Add two matrices.
4. Multiply two matrices.

---

## Experiment 4: List Comprehensions

1. Generate cubes of numbers from 1 to 10.
2. Create a list containing odd numbers.
3. Convert all names in a list to uppercase.

---

# Requirements

* Python 3.x

---

# Procedure

## Experiment 1: Introduction to Python Lists

### Create a List of Subjects

```python
subjects = ["Mathematics", "Physics", "Chemistry", "Biology", "English"]
```

### Print First and Last Element

```python
print(subjects[0])
print(subjects[-1])
```

### Replace Third Subject

```python
subjects[2] = "Computer Science"
print(subjects)
```

---

## Experiment 2: List Operations and Methods

### Create a List of Integers

```python
numbers = [10, 5, 8, 3, 15]
```

### Add Two Elements

```python
numbers.append(20)
numbers.append(25)
```

### Remove One Element

```python
numbers.remove(8)
```

### Sort the List

```python
numbers.sort()
```

### Reverse the List

```python
numbers.reverse()
```

### Display Final List

```python
print(numbers)
```

---

## Experiment 3: Nested Lists and Matrix Operations

### Create a 3×3 Matrix

```python
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
```

### Print Diagonal Elements

```python
for i in range(3):
    print(matrix[i][i])
```

### Matrix Addition

```python
A = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]

B = [
    [9, 8, 7],
    [6, 5, 4],
    [3, 2, 1]
]

result = []

for i in range(3):
    row = []
    for j in range(3):
        row.append(A[i][j] + B[i][j])
    result.append(row)

print(result)
```

### Matrix Multiplication

```python
result = [[0]*3 for _ in range(3)]

for i in range(3):
    for j in range(3):
        for k in range(3):
            result[i][j] += A[i][k] * B[k][j]

print(result)
```

---

## Experiment 4: List Comprehensions

### Generate Cubes from 1 to 10

```python
cubes = [x**3 for x in range(1, 11)]
print(cubes)
```

### Generate Odd Numbers

```python
odd_numbers = [x for x in range(1, 21) if x % 2 != 0]
print(odd_numbers)
```

### Convert Names to Uppercase

```python
names = ["ram", "sita", "hari"]

upper_names = [name.upper() for name in names]

print(upper_names)
```

---

# Observation

### Experiment 1

* Lists allow easy storage and modification of multiple values.
* Elements can be accessed using indexing.

### Experiment 2

* List methods simplify insertion, deletion, sorting, and rearrangement operations.

### Experiment 3

* Nested lists can represent matrices.
* Matrix operations can be implemented using loops.

### Experiment 4

* List comprehensions provide concise and efficient code.
* Data transformation becomes easier using comprehensions.

---

# Result

Successfully performed list creation, modification, list method operations, matrix manipulation using nested lists, and data transformation using list comprehensions.

---

# Conclusion

This laboratory session introduced Python Lists and their applications. Various list operations, nested lists, matrix manipulations, and list comprehensions were implemented successfully. These concepts provide a strong foundation for Machine Learning, where data is often stored, transformed, and processed using list-based structures before advanced libraries such as NumPy and Pandas are introduced.
