# UnassignedVariableError

**Category:** ERROR | **Subcategory:** Scope

## Summary
Reading variable declared without initialization.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless UnassignedVariableError:
  display "Caught UnassignedVariableError" ?color=#f59e0b
```
