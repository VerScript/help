# xnor — Logical Equivalence / Negated XOR

**Category:** Logical Operator  
**Identifier:** `xnor`

---

## Summary
Returns true if both operands have identical boolean truth values.

## Syntax
```verscript
exprA xnor exprB
```

**Parameters:** exprA (bool), exprB (bool)  
**Returns:** bool  
**Paired Keywords:** `xor, and, or`

## Code Example
```verscript
stateA : true
stateB : true
if stateA xnor stateB:
    display "States are synchronized" ?color=#00FFCC
```

---
*Part of the official VerScript Language Reference.*
