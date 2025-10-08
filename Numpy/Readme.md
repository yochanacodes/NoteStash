# NumPy Notes

Numpy stands for Numerical Python . It is a library consisting of multidimensional array objects and a collection of routines for processing arrays.

We can perform the following operations using numpy:


- Mathematical and logical operations on arrays.
- Fourier transforms and routines for shape manipulation.
- Work with linear algebra using built-in functions.  
- Generate random numbers for statistical simulations and modeling.

---

## Installation

Install NumPy quickly using `pip`:


```bash
pip install numpy
```


## The `ndarray` Object

The core of NumPy is the **N-dimensional array object**, known as `ndarray`.  
It is a fast, flexible container for large datasets of the same data type.

---

### Key Characteristics

- Each element in an `ndarray` occupies the same amount of memory.  
- Elements are accessed using zero-based indexing.  
- All elements share a common data type (`dtype`).  
- The array interface ensures efficient memory handling and computation.

---

## Creating an `ndarray`

The basic `ndarray` is created using the  function.
```python
numpy.array()
```

### Example

```python
import numpy as np

# Creating a simple ndarray
arr = np.array([1, 2, 3, 4])
print(arr)
```
