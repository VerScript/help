# unpack — Structured Destructuring Assignment

**Category:** Destructuring Assignment  
**Identifier:** `unpack`

---

## Summary
Unpacks elements from an array or entity fields directly into multiple variables.

## Syntax
```verscript
unpack [var1, var2] : array_or_tuple
```

**Parameters:** Target variable list and source collection  
**Returns:** Binds variables  
**Paired Keywords:** `set, :`

## Code Example
```verscript
coords : [100, 250]
unpack [x, y] : coords
display "X: " + x + ", Y: " + y
```

---
*Part of the official VerScript Language Reference.*
