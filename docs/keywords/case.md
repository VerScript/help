# case — Pattern Matching Branch Selector

**Category:** Pattern Branch  
**Identifier:** `case`

---

## Summary
Defines an individual matching branch and statement within a match expression.

## Syntax
```verscript
case pattern : action
```

**Parameters:** pattern (literal or wildcard `_`)  
**Returns:** Branch evaluation result  
**Paired Keywords:** `match, with`

## Code Example
```verscript
code : 200
match code with:
    case 200: display "OK"
    case 404: display "Not Found"
    case _: display "Server Error"
```

---
*Part of the official VerScript Language Reference.*
