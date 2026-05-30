# Lab Report

## Lab Session 2: Working with Dictionary and Pandas DataFrame

### Student Information

| Field    | Details                |
| -------- | ---------------------- |
| Name     | Maheshwar Pant         |
| Roll No. | 230322                 |
| Faculty  | Science and Technology |
| Subject  | Machine Learning       |
| Lab No.  | 2                      |
| Date     | 2083-02-12             |

---

# Title

**Working with Dictionary and Pandas DataFrame in Python**

---

# Objective

The objectives of this laboratory session are:

1. To understand the concept of Python dictionaries.
2. To perform various operations on dictionaries such as insertion, deletion, updating, and traversal.
3. To understand the structure and importance of Pandas DataFrames.
4. To perform data manipulation and analysis using DataFrame operations.
5. To develop practical skills for handling structured data used in Machine Learning.

---

# Theory

## Part I: Dictionary in Python

A dictionary is a built-in Python data structure used to store data in the form of key-value pairs. Each key in a dictionary must be unique and is used to access its corresponding value.

### Features of Dictionary

* Stores data in key-value format.
* Mutable (can be modified after creation).
* Allows different data types.
* Provides fast retrieval of information.
* Frequently used for configuration settings and mapping operations.

### Example

```python
student = {
    "name": "Ram",
    "age": 20,
    "faculty": "BCE"
}
```

### Applications of Dictionaries

* Storing student records.
* Configuration settings.
* Database-like structures.
* JSON data representation.
* Machine Learning parameter storage.

---

## Part II: Pandas DataFrame

A DataFrame is a two-dimensional tabular data structure provided by the Pandas library. It organizes data into rows and columns similar to Excel spreadsheets or SQL tables.

### Features of DataFrame

* Handles large datasets efficiently.
* Supports labeled rows and columns.
* Enables filtering, sorting, and aggregation.
* Provides statistical analysis tools.
* Supports importing and exporting data files.

### Applications of DataFrame

* Data preprocessing.
* Exploratory Data Analysis (EDA).
* Feature engineering.
* Machine Learning dataset preparation.
* Data visualization.

---

# Relevance to Machine Learning

Machine Learning algorithms require data to be cleaned, organized, and transformed before training. Pandas DataFrames are the standard structure used for dataset manipulation, while dictionaries are useful for storing hyperparameters, labels, mappings, and configuration information. Understanding these structures is essential for data preprocessing and model development workflows.

---

# Problem Statement / Questions to be Solved

## Part I: Dictionary

Perform the following operations:

1. Create a dictionary.
2. Access values using keys.
3. Access values using the `get()` method.
4. Add a new item.
5. Update an existing value.
6. Remove an item using `del`.
7. Remove an item using `pop()`.
8. Remove the last inserted item using `popitem()`.
9. Clear the dictionary.
10. Copy a dictionary.
11. Display all keys.
12. Display all values.
13. Display all key-value pairs.
14. Check whether a key exists.
15. Find the length of the dictionary.
16. Loop through keys.
17. Loop through values.
18. Loop through items.

## Part II: Pandas DataFrame

Perform the following operations:

1. Create a DataFrame containing Name, Age, and Marks.
2. Display the first five rows.
3. Display the last five rows.
4. Find the shape of the DataFrame.
5. Display column names.
6. Display DataFrame information.
7. Generate statistical summary.
8. Select a single column.
9. Select multiple columns.
10. Display the first row using `iloc`.
11. Display the first row using `loc`.
12. Access a specific cell value.
13. Filter students with Marks greater than 80.
14. Filter students with Age greater than 20 and Marks greater than 75.
15. Add a Grade column.
16. Increase all Marks by 5.
17. Update Ram's Marks to 95.
18. Remove the Age column.
19. Remove the first row.
20. Sort by Marks in ascending order.
21. Sort by Marks in descending order.
22. Concatenate two DataFrames.
23. Read data from a CSV file.
24. Write data to a CSV file.
25. Read data from an Excel file.
26. Write data to an Excel file.

---

# Requirements

* Python 3.x
* Pandas Library

```bash
pip install pandas
```

---

# Procedure

(Keep all the Dictionary and DataFrame operation code blocks from your existing report here.)

---

# Observation

### Dictionary

* Data can be stored efficiently using key-value pairs.
* Values can be updated dynamically.
* Keys provide fast access to information.

### DataFrame

* DataFrames provide spreadsheet-like data handling.
* Filtering and sorting simplify analysis.
* Statistical functions help summarize datasets quickly.

---

# Result

Successfully performed all dictionary and DataFrame operations including creation, modification, deletion, filtering, sorting, and file handling. The practical exercise demonstrated how these structures are used for data manipulation tasks commonly encountered in Machine Learning.

---

# Conclusion

This laboratory session provided practical experience with Python Dictionaries and Pandas DataFrames. Dictionaries enable efficient key-value data storage, while DataFrames provide powerful tools for managing and analyzing tabular data. These concepts form a fundamental foundation for Machine Learning, where data preprocessing, transformation, and analysis are critical steps before model training and evaluation.
