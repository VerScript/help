# xand — Cross Logical Conjunction

**Category:** Logical Operator  
**Identifier:** `xand`

---

## Summary
Specialized non-associative logical conjunction operator for strict truth state validation.

## Syntax
```verscript
exprA xand exprB
```

**Parameters:** exprA (bool), exprB (bool)  
**Returns:** bool  
**Paired Keywords:** `and, nand`

## Code Example
```verscript
cond1 : true
cond2 : true
res : cond1 xand cond2
display "XAND: " + res
```

---
*Part of the official VerScript Language Reference.*
