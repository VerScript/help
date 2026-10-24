# extends — DataType Specialization & Inheritance

**Category:** Type Inheritance  
**Identifier:** `extends`

---

## Summary
Inherits and extends fields and methods from a base DataType or Class.

## Syntax
```verscript
DataType SubType extends BaseType:
    ...
```

**Parameters:** BaseType (DataType identifier)  
**Returns:** Extended subtype definition  
**Paired Keywords:** `DataType, class`

## Code Example
```verscript
DataType Employee extends Person:
    department : str
```

---
*Part of the official VerScript Language Reference.*
