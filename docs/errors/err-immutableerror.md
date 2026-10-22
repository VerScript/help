# ImmutableError

**Category:** ERROR | **Subcategory:** Storage

## Summary
Attempting to reassign a const variable.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless ImmutableError:
  display "Caught ImmutableError" ?color=#f59e0b
```
