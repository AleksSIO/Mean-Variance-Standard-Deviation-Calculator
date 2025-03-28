# 🧮 Mean-Variance-Standard Deviation Calculator

This project is part of the [freeCodeCamp Data Analysis with Python](https://www.freecodecamp.org/learn/data-analysis-with-python/) certification.  
It builds a simple statistics calculator using NumPy to compute metrics like **mean**, **variance**, **standard deviation**, **min**, **max**, and **sum** on a 3×3 matrix.

---

## 📁 Project Structure

```
mean_var_std.py         # Script containing the calculation logic  
main.py                 # Development entrypoint to test your function  
test_module.py          # Unit tests for validation  
```

---

## 📊 Features

- Accepts a list of **9 numerical values**  
- Converts the list into a **3×3 NumPy matrix**  
- Computes the following statistics across:
  - **Each column**
  - **Each row**
  - **Entire matrix**
- Returns the results in a dictionary format with the following keys:
  - `'mean'`, `'variance'`, `'standard deviation'`, `'max'`, `'min'`, `'sum'`

---

## 🧪 Technologies Used

- **Python 3**
- **NumPy**

---

## 🚀 How to Run the Project

1. Install the required library:

```bash
pip install numpy
```

2. Run the script:

```bash
python main.py
```

The script will:

- Execute the `calculate()` function with a sample list  
- Print the results  
- Run unit tests from `test_module.py`

---

## 🧾 Example

Input:
```python
[0, 1, 2, 3, 4, 5, 6, 7, 8]
```

Output:
```python
{
  'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  'variance': [[6.0, 6.0, 6.0], [0.666..., 0.666..., 0.666...], 6.666...],
  'standard deviation': [[2.449..., 2.449..., 2.449...], [0.816..., 0.816..., 0.816...], 2.581...],
  'max': [[6, 7, 8], [2, 5, 8], 8],
  'min': [[0, 1, 2], [0, 3, 6], 0],
  'sum': [[9, 12, 15], [3, 12, 21], 36]
}
```

---

## 📚 Notes

- Input must be a list of exactly **9 numbers**, otherwise a `ValueError` is raised.
- All calculations are done using NumPy vectorized operations for performance.

