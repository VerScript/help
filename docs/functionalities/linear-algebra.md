# How to Compute Matrix Inverses, Determinants, and Multiplications

> **Category**: `functionality` | **Subcategory**: Mathematics

## Overview
Using the Matrix standard library for high-speed deterministic operations on 2D arrays.

## Example
```verscript
load Matrix
set A : [[4, 7], [2, 6]]
set det : Matrix.det(A)
set inv : Matrix.inv(A)
display "Determinant: " + det ?color=#00FFCC
display "Inverse Matrix: " + inv ?color=#22c55e
```

