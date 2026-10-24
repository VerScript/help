# nand — Negated Logical AND Gate

**Category:** Logical Operator  
**Identifier:** `nand`

---

## Summary
Returns false only when both operands are true; otherwise returns true.

## Syntax
```verscript
exprA nand exprB
```

**Parameters:** exprA (bool), exprB (bool)  
**Returns:** bool  
**Paired Keywords:** `if, nor, xor`

## Code Example
```verscript
flagA : true
flagB : true
result : flagA nand flagB
display "NAND Result: " + result  ! Displays false
```

---
*Part of the official VerScript Language Reference.*
