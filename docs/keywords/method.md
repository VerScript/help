# method — Object & Class Method Declaration

**Category:** Class Method Declaration  
**Identifier:** `method`

---

## Summary
Declares a member function within a class definition with access to instance state.

## Syntax
```verscript
method methodName(args):
    ...
```

**Parameters:** methodName (identifier), args  
**Returns:** Defines member method  
**Paired Keywords:** `class, func, def, reply`

## Code Example
```verscript
class Account:
    method deposit(amount):
        balance : balance + amount
```

---
*Part of the official VerScript Language Reference.*
