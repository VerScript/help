# InvalidOperandError

**Category:** ERROR | **Subcategory:** Expression

## Summary
Applying an operator to incompatible types (e.g. adding boolean to array).

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless InvalidOperandError:
  display "Caught InvalidOperandError" ?color=#f59e0b
```
