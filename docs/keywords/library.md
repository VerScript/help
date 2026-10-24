# library — Canonical Module Definition Alias

**Category:** Module Declaration  
**Identifier:** `library`

---

## Summary
Full keyword alias for declaring modular library units and namespaces.

## Syntax
```verscript
library MyLib:
    ...
```

**Parameters:** MyLib (identifier)  
**Returns:** Library namespace object  
**Paired Keywords:** `lib, export, import`

## Code Example
```verscript
library Geometry:
    export def area(w, h):
        reply w * h
```

---
*Part of the official VerScript Language Reference.*
