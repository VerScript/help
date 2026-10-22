# UndefinedVariableError

**Category:** ERROR | **Subcategory:** Scope & Resolution

## Summary
Raised when accessing an identifier that has not been declared with 'set', 'def', or passed as an argument in the current scope.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  set val : missingVar
unless UndefinedVariableError:
  display "Variable was not defined; fallback activated." ?color=#f59e0b
```
