# ScopeViolationError

**Category:** ERROR | **Subcategory:** Purity & Architecture

## Summary
Raised when pure functions (func) attempt to mutate external variables or access private/unscoped identifiers.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
set globalCount : 0
! Inside func, modifying globalCount raises ScopeViolationError
```
