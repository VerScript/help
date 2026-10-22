# DivisionByZeroError

**Category:** ERROR | **Subcategory:** Arithmetic

## Summary
Triggered whenever an arithmetic division (/) or remainder (%) operation receives a zero denominator.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  set res : 100 / divisor
unless DivisionByZeroError:
  display "Cannot divide by zero!" ?color=#f59e0b
  set res : 0
```
