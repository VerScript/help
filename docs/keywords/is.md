# is — Dynamic Type & State Predicate

**Category:** Type & Identity Predicate  
**Identifier:** `is`

---

## Summary
Tests whether a variable conforms to a primitive type or numeric characteristic (even/odd).

## Syntax
```verscript
expression is type_or_predicate
```

**Parameters:** expression (any), type (num, str, bool, arr, entity, even, odd)  
**Returns:** bool  
**Paired Keywords:** `if, guard, even, odd`

## Code Example
```verscript
val : 42
if val is num:
    display "Value is numeric" ?color=#00FFCC
if val is even:
    display "Value is an even integer"
```

---
*Part of the official VerScript Language Reference.*
