# Matrix

**Category:** LIBRARY | **Subcategory:** Standard Library (Math)

## Summary
Deterministic linear algebra and matrix operations: determinants, inverses, eigenvalues, decompositions, and element-wise arithmetic.

## Syntax
```verscript
load Matrix
Matrix.det(m)
Matrix.inv(m)
Matrix.mult(a, b)
Matrix.identity(n)
```

## Parameters / Arguments
- `matrix` *(2D array (arr))*: undefined

## Runnable Code Example
```verscript
load Matrix
set M : [[2, 1], [5, 7]]
display "Det: " + Matrix.det(M) ?color=#00FFCC
display "Trace: " + Matrix.trace(M) ?color=#38bdf8
```
