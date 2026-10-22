# LoopStepError

**Category:** ERROR | **Subcategory:** Iteration

## Summary
Step of 0 passed to range loop.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless LoopStepError:
  display "Caught LoopStepError" ?color=#f59e0b
```
