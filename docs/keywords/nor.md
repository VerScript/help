# nor — Negated Logical OR Gate

**Category:** Logical Operator  
**Identifier:** `nor`

---

## Summary
Returns true only when both operands are false; otherwise returns false.

## Syntax
```verscript
exprA nor exprB
```

**Parameters:** exprA (bool), exprB (bool)  
**Returns:** bool  
**Paired Keywords:** `if, nand, xor`

## Code Example
```verscript
a : false
b : false
if a nor b:
    display "Both are inactive" ?color=#38bdf8
```

---
*Part of the official VerScript Language Reference.*
