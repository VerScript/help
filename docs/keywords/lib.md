# lib — Modular Library Definition

**Category:** Module Declaration  
**Identifier:** `lib`

---

## Summary
Declares a reusable library namespace containing exported functions, classes, and constants.

## Syntax
```verscript
lib LibraryName:
    export def method(): ...
```

**Parameters:** LibraryName (identifier)  
**Returns:** Library module object  
**Paired Keywords:** `export, load, import, public`

## Code Example
```verscript
lib MathUtils:
    export def doubleVal(n):
        reply n * 2
```

---
*Part of the official VerScript Language Reference.*
