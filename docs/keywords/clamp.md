# clamp — Range Value Boundary Clamping

**Category:** Built-in Math Function  
**Identifier:** `clamp`

---

## Summary
Constrains a value within a specified minimum and maximum range.

## Syntax
```verscript
clamp(value, minVal, maxVal)
```

**Parameters:** value (num), minVal (num), maxVal (num)  
**Returns:** num (clamped value)  
**Paired Keywords:** `min, max`

## Code Example
```verscript
hp : clamp(currentHp, 0, 100)
display "Health: " + hp
```

---
*Part of the official VerScript Language Reference.*
