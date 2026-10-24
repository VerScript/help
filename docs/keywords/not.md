# not — Unary Logical Inversion

**Category:** Logical Operator  
**Identifier:** `not`

---

## Summary
Inverts the truth value of a boolean expression.

## Syntax
```verscript
not expr
```

**Parameters:** expr (bool)  
**Returns:** bool (inverted boolean value)  
**Paired Keywords:** `if, unless, and, or`

## Code Example
```verscript
isReady : false
if not isReady:
    display "System warming up..." ?color=#f59e0b
```

---
*Part of the official VerScript Language Reference.*
