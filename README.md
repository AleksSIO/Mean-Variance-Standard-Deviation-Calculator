# Mean-Variance-Standard Deviation Calculator

This is the solution to the **Mean-Variance-Standard Deviation Calculator** project from the [freeCodeCamp Data Analysis with Python](https://www.freecodecamp.org/learn/data-analysis-with-python/) certification.

## 📌 Project Description

The function `calculate` receives a list of **9 numerical values**, reshapes it into a **3x3 matrix**, and returns a dictionary with the following statistical measures:

- Mean
- Variance
- Standard Deviation
- Max
- Min
- Sum

Each metric includes:
- Column-wise values
- Row-wise values
- Overall value

## 📁 File Structure

- `mean_var_std.py` → Contains the `calculate` function.

## ▶️ Usage

```python
from mean_var_std import calculate

print(calculate([0, 1, 2, 3, 4, 5, 6, 7, 8]))
