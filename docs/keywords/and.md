# and — Short-Circuit Logical Conjunction

**Category:** Logical Operator  
**Identifier:** `and`

---

## Summary
Evaluates whether two boolean expressions are both true, short-circuiting evaluation if the left operand is false.

## Syntax
```verscript
exprA and exprB
```

**Parameters:** exprA (bool), exprB (bool)  
**Returns:** bool (true if both operands evaluate to true)  
**Paired Keywords:** `if, while, guard, not, or`

## Code Example
```verscript
isValid : true
isAdmin : true
if isValid and isAdmin:
    display "Access Granted" ?color=#00FFCC
```

---
*Part of the official VerScript Language Reference.*
