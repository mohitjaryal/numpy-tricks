# 🔢 NumPy Tricks & Useful Functions

A hands-on collection of **essential NumPy functions** with clean examples — all in one Jupyter Notebook. Built while following the [CampusX](https://www.youtube.com/@campusx-official) NumPy session.

---

## 📌 About

This repository contains a Jupyter Notebook (`numpy-ticks.ipynb`) covering the most useful NumPy utility functions with practical 1D and 2D array examples. Great as a **quick reference** while doing Data Science or ML projects.

---

## 📂 Repository Structure

```
numpy-tricks/
│
├── numpy-ticks.ipynb   # Main notebook with all NumPy tricks
├── README.md           # You are here
└── LICENSE             # MIT License
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- NumPy
- Jupyter Notebook / JupyterLab

### Installation

```bash
# Clone the repository
git clone https://github.com/mohitjaryal/numpy-tricks.git

# Navigate into the directory
cd numpy-tricks

# Install dependencies
pip install numpy jupyter

# Launch the notebook
jupyter notebook numpy-ticks.ipynb
```

---

## 📖 Topics Covered

| # | Function | Description |
|---|----------|-------------|
| 1 | `np.sort()` | Returns a sorted copy of an array (row-wise & column-wise) |
| 2 | `np.append()` | Appends values at the end of an array along an axis |
| 3 | `np.concatenate()` | Joins a sequence of arrays along an existing axis |
| 4 | `np.unique()` | Returns unique elements from an array |
| 5 | `np.expand_dims()` | Expands the dimensions of an array |
| 6 | `np.where()` | Returns indices where condition is true / conditional replacement |
| 7 | `np.argmax()` | Returns index of the maximum element along an axis |
| 8 | `np.argmin()` | Returns index of the minimum element along an axis |
| 9 | `np.cumsum()` | Computes the cumulative sum of array elements |
| 10 | `np.cumprod()` | Computes the cumulative product of array elements |
| 11 | `np.percentile()` | Finds the nth percentile of the array data |
| 12 | `np.histogram()` | Shows frequency distribution of data |
| 13 | `np.corrcoef()` | Returns Pearson correlation coefficients |
| 14 | `np.isin()` | Checks whether elements of an array exist in another array |
| 15 | `np.flip()` | Reverses the order of elements along a specified axis |
| 16 | `np.put()` | Replaces specific elements of an array with given values |
| 17 | `np.delete()` | Deletes elements from an array along an axis |
| 18 | `np.union1d()` | Computes the union of two arrays |
| 19 | `np.intersect1d()` | Computes the intersection of two arrays |
| 20 | `np.setdiff1d()` | Computes the set difference of two arrays |
| 21 | `np.setxor1d()` | Computes the symmetric difference (XOR) of two arrays |
| 22 | `np.clip()` | Limits (clips) values in an array to a given min and max |

---

## 💡 Code Highlights

```python
import numpy as np

# np.where() — conditional replacement
a = np.random.randint(1, 100, 15)
np.where(a > 50, 0, a)          # replace values > 50 with 0
np.where(a % 2 == 0, 0, a)      # replace even numbers with 0
np.where(a % 2 != 0, 1, 0)      # odd → 1, even → 0

# np.corrcoef() — correlation between salary and experience
salary    = np.array([20000, 40000, 25000, 35000, 60000])
experience = np.array([1, 3, 2, 4, 2])
np.corrcoef(salary, experience)

# np.clip() — limit values between 25 and 75
np.clip(a, a_min=25, a_max=75)

# Set operations
m = np.array([1, 2, 3, 4, 5])
n = np.array([3, 4, 5, 6, 7])
np.union1d(m, n)       # [1, 2, 3, 4, 5, 6, 7]
np.intersect1d(m, n)   # [3, 4, 5]
np.setdiff1d(m, n)     # [1, 2]
np.setxor1d(m, n)      # [1, 2, 6, 7]
```

---

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Latest-013243?style=flat&logo=numpy)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)

---

## 🎥 Reference

This notebook is based on the **CampusX NumPy Session**.  
📺 Watch here → [CampusX YouTube](https://www.youtube.com/@campusx-official)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Connect with Me

| Platform | Link |
|----------|------|
| 🌐 Website | [mohitjaryal.online](https://mohitjaryal.online) |
| 💼 LinkedIn | [in/mohitjaryal](https://www.linkedin.com/in/mohitjaryal) |
| 🐦 Twitter/X | [@mohitjaryal04](https://x.com/mohitjaryal04) |
| 💻 GitHub | [mohitjaryal](https://github.com/mohitjaryal) |
| 🧩 LeetCode | [mohitjaryal](https://leetcode.com/u/mohitjaryal) |
| 🧩 Hackerrank | [mohitjaryal](https://hackerrank.com/u/mohitjaryal) |

---

<div align="center">

**⭐ If this repo helped you, consider giving it a star! It motivates me to keep learning and sharing.**

*Made with 💙 by [Mohit Jaryal](https://mohitjaryal.online)*

</div>
