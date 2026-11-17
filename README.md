# python-kwargs-total-marks
A simple Python program using **kwargs to calculate the total marks of multiple subjects.
# Python Total Marks Calculator Using **kwargs

## About Project
This is a beginner-friendly Python program that calculates the total marks of multiple subjects using the `**kwargs` concept.

## Concepts Used
- Python Functions
- `**kwargs`
- For Loop
- Dictionary `items()`
- Return Statement

## Code
```python
def total(**kwargs):
    sum = 0

    for subject, marks in kwargs.items():
        sum = sum + marks

    return sum

print(total(maths=80, python=90, cpp=75))
```

## Output
```text
245
```

## How It Works
1. `**kwargs` accepts multiple keyword arguments.
2. `items()` accesses subject names and marks.
3. The for loop adds all marks.
4. The function returns the total marks.

## Author
Python Beginner Project

## Language
Python
