# hypot — Euclidean Distance Hypotenuse

**Category:** Built-in Math Function  
**Identifier:** `hypot`

---

## Summary
Computes $sqrt{x^2 + y^2}$ without intermediate overflow or underflow.

## Syntax
```verscript
hypot(x, y)
```

**Parameters:** x (num), y (num)  
**Returns:** num (hypotenuse length)  
**Paired Keywords:** `sqrt, sin, cos`

## Code Example
```verscript
dist : hypot(3, 4)
display "Hypotenuse: " + dist  ! Outputs 5
```

---
*Part of the official VerScript Language Reference.*
