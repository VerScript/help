# stroke — Border & Outline Specification

**Category:** Style Specification  
**Identifier:** `stroke`

---

## Summary
Specifies outline color and border width for drawing primitives.

## Syntax
```verscript
stroke(color, width) or ?stroke=#hex ?strokeWidth=2
```

**Parameters:** color (hex), width (num)  
**Returns:** Applies stroke style  
**Paired Keywords:** `fill, draw, line`

## Code Example
```verscript
draw rect(20, 20, 80, 80) ?stroke=#00FFCC ?strokeWidth=2
```

---
*Part of the official VerScript Language Reference.*
