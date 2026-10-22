# EntityError

**Category:** ERROR | **Subcategory:** Object

## Summary
Invalid property access or mutation on entity.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless EntityError:
  display "Caught EntityError" ?color=#f59e0b
```
