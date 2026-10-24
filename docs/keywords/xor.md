# xor — Exclusive Disjunction

**Category:** Logical Operator  
**Identifier:** `xor`

---

## Summary
Returns true if exactly one operand is true and the other is false.

## Syntax
```verscript
exprA xor exprB
```

**Parameters:** exprA (bool), exprB (bool)  
**Returns:** bool  
**Paired Keywords:** `xnor, and, or`

## Code Example
```verscript
hasCoupon : true
hasDiscount : false
if hasCoupon xor hasDiscount:
    display "Valid single promotion" ?color=#10b981
```

---
*Part of the official VerScript Language Reference.*
