# Matrix (Constructor & Class)

**Category:** LIBRARY | **Subcategory:** Matrix Math

## Summary
Linear algebra library and matrix class supporting constructors, determinants, matrix multiplication, inversion, and decomposition.

## Syntax
```verscript
load Matrix
set m : Matrix(rows, cols, defaultValue)
Matrix.det(m)
Matrix.identity(n)
```

## Description
`Matrix` can be used statically (`Matrix.multiply(A, B)`) or instantiated as an entity (`set m : Matrix(3, 3, 0); m.det()`).

## Parameters / Arguments
- `rows` *(num)*: Number of rows.
- `cols` *(num)*: Number of columns.
- `defaultVal` *(num)*: Optional initial element value (default 0).

**Return Value / Type:** `Matrix entity or 2D Array`

## Paired Keywords & Related Topics
`load`, `Vector`, `Math`, `construct`

## Runnable Code Example
```verscript
load Matrix
set m : Matrix.identity(3)
display "Determinant: " + Matrix.det(m)
```
