# pkg — Package Declaration & Scoping

**Category:** Package Namespace  
**Identifier:** `pkg`

---

## Summary
Encapsulates source units into a distribution package namespace for the VerScript Package Manager.

## Syntax
```verscript
pkg package.name
```

**Parameters:** package.name (qualified identifier)  
**Returns:** Enforces package scope  
**Paired Keywords:** `import, export, lib`

## Code Example
```verscript
pkg org.verscript.net
lib HttpClient:
    ...
```

---
*Part of the official VerScript Language Reference.*
