# or — Short-Circuit Logical Disjunction

**Category:** Logical Operator  
**Identifier:** `or`

---

## Summary
Evaluates whether at least one of two boolean expressions is true, short-circuiting if the left operand is true.

## Syntax
```verscript
exprA or exprB
```

**Parameters:** exprA (bool), exprB (bool)  
**Returns:** bool (true if either operand is true)  
**Paired Keywords:** `if, while, guard, and, not`

## Code Example
```verscript
isOwner : false
isModerator : true
if isOwner or isModerator:
    display "Action Allowed" ?color=#00FFCC
```

---
*Part of the official VerScript Language Reference.*
