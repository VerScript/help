# IndexOutOfBoundsError

**Category:** ERROR | **Subcategory:** Array

## Summary
Index exceeds array bounds.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless IndexOutOfBoundsError:
  display "Caught IndexOutOfBoundsError" ?color=#f59e0b
```
