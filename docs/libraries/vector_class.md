# Vector (Constructor & Class)

**Category:** LIBRARY | **Subcategory:** Vector Math

## Summary
2D, 3D, and n-dimensional geometric vector library and class (dot product, cross product, magnitude, normalize).

## Syntax
```verscript
load Vector
set v : Vector(x, y, z)
v.magnitude()
Vector.dot(v1, v2)
```

## Description
Provides high-speed vector arithmetic. Supports instance method calls (`v.magnitude()`) as well as static library functions (`Vector.cross(u, v)`).

## Parameters / Arguments
- `x` *(num)*: X component.
- `y` *(num)*: Y component.
- `z` *(num)*: Optional Z component (default 0).

**Return Value / Type:** `Vector entity`

## Paired Keywords & Related Topics
`load`, `Matrix`, `Math`, `construct`

## Runnable Code Example
```verscript
load Vector
set v1 : Vector(1, 0, 0)
set v2 : Vector(0, 1, 0)
set v3 : Vector.cross(v1, v2)
display v3.z  ! 1
```
