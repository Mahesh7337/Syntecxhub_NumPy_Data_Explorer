# NumPy Data Explorer

## 📌 Project Description
**NumPy Data Explorer** is a foundational project aimed at understanding and
applying core NumPy concepts used in data analysis and scientific computing.
The project demonstrates efficient numerical computation using NumPy arrays
and compares their performance with standard Python lists.

---

## 🎯 Objectives
- Learn NumPy array creation, indexing, and slicing
- Perform mathematical and statistical operations on datasets
- Apply reshaping and broadcasting for efficient computation
- Implement save and load operations for NumPy arrays
- Compare computational performance of NumPy arrays and Python lists

---

## 🧠 Concepts Implemented
- 1D and 2D array creation
- Indexing and slicing
- Mathematical operations (sum, mean, max)
- Axis-wise operations (row-wise, column-wise)
- Array reshaping
- Broadcasting
- File I/O using `.npy` format
- Performance benchmarking

---

## 🛠 Tools & Technologies
- Python 3
- NumPy

---

## 📂 Project Structure
NumPy-Data-Explorer/
│
├── numpy_data_explorer.py
│ → Demonstrates NumPy fundamentals and operations
│
├── performance_comparison.py
│ → Compares execution time of NumPy arrays and Python lists
│
├── sample_array.npy
│ → Stored NumPy array file
│
└── README.md


---

## ⚡ Performance Comparison (Key Highlight)

To evaluate performance, the same arithmetic operation was performed on
**one million elements** using:

- **Standard Python list** with a loop
- **NumPy array** with vectorized operations

Execution time was measured using Python’s `time` module.

### 🔍 Observation
NumPy arrays executed significantly faster than Python lists due to:
- Vectorization
- Optimized C-based internal implementation
- Reduced Python-level looping

### ✅ Conclusion
**NumPy is more efficient and faster than standard Python lists for large-scale numerical computations.**


