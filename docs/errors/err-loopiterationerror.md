# LoopIterationError

**Category:** ERROR | **Subcategory:** Iteration

## Summary
Invalid iteration parameters or modifying collection while iterating.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless LoopIterationError:
  display "Caught LoopIterationError" ?color=#f59e0b
```
