# step — Customizable Loop Stride

**Category:** Loop Stride Control  
**Identifier:** `step`

---

## Summary
Controls the increment or decrement stride when iterating over numeric ranges.

## Syntax
```verscript
for i in start .. end step stride:
    ...
```

**Parameters:** stride (positive integer increment)  
**Returns:** Advances loop counter by stride value  
**Paired Keywords:** `for, in, ..`

## Code Example
```verscript
for i in 0 .. 10 step 2:
    display "Even index: " + i
```

---
*Part of the official VerScript Language Reference.*
