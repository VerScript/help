# config — Compiler & Runtime Directive Block

**Category:** Configuration & Directives  
**Identifier:** `config`

---

## Summary
Declares execution configuration options, optimization levels, or runtime constraints for a script.

## Syntax
```verscript
config:
  key : value
```

**Parameters:** Configuration key-value pairs  
**Returns:** Configures script runtime environment  
**Paired Keywords:** `pragma, header`

## Code Example
```verscript
config:
    strictTypes : true
    optimize : 2
```

---
*Part of the official VerScript Language Reference.*
