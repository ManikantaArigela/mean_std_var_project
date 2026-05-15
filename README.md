# Mean-Variance-Standard Deviation Calculator

This project is part of the freeCodeCamp Data Analysis with Python Certification.

The project uses NumPy to calculate:

- Mean
- Variance
- Standard Deviation
- Maximum value
- Minimum value
- Sum

for rows, columns, and the entire matrix.

---

# Technologies Used

- Python
- NumPy

---

# Project Structure

```text
project-folder/
│
├── mean_var_std.py
├── main.py
├── test_module.py
└── README.md
```

---

# Requirements

Install NumPy before running the project.

```bash
pip install numpy
```

---

# How the Project Works

The function accepts a list containing 9 numbers.

Example:

```python
[0,1,2,3,4,5,6,7,8]
```

The list is converted into a 3 × 3 NumPy matrix.

```python
[[0,1,2],
 [3,4,5],
 [6,7,8]]
```

Then the program calculates statistical values for:

- Columns
- Rows
- Entire matrix

---

# Example Output

```python
{
 'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],

 'variance': [
     [6.0, 6.0, 6.0],
     [0.6666666666666666,
      0.6666666666666666,
      0.6666666666666666],
     6.666666666666667
 ],

 'standard deviation': [
     [2.449489742783178,
      2.449489742783178,
      2.449489742783178],

     [0.816496580927726,
      0.816496580927726,
      0.816496580927726],

     2.581988897471611
 ],

 'max': [[6, 7, 8], [2, 5, 8], 8],

 'min': [[0, 1, 2], [0, 3, 6], 0],

 'sum': [[9, 12, 15], [3, 12, 21], 36]
}
```

---

# How to Run

Run the main file:

```bash
python main.py
```

---

# Running Tests

Run unit tests using:

```bash
python test_module.py
```

OR

```bash
python -m unittest
```

---

# Error Handling

If the input list does not contain exactly 9 numbers, the function raises:

```python
ValueError: List must contain nine numbers.
```

---

# Skills Learned

Through this project, I learned:

- NumPy arrays
- Matrix reshaping
- Statistical operations
- Axis operations
- Python dictionaries
- Exception handling
- Unit testing

---

# Author

Developed as part of the freeCodeCamp Data Analysis with Python Certification.
