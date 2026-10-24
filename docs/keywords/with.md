# with — Contextual Binding & Match Target

**Category:** Context & Pattern Matching  
**Identifier:** `with`

---

## Summary
Binds expression targets into match evaluation or scoped contextual resources.

## Syntax
```verscript
match target with:
  case pattern: ...
```

**Parameters:** target (expression)  
**Returns:** Evaluated branch result  
**Paired Keywords:** `match, case`

## Code Example
```verscript
role : "admin"
match role with:
    case "admin": display "Superuser Access"
    case "guest": display "Read Only"
    case _: display "Unknown Role"
```

---
*Part of the official VerScript Language Reference.*
