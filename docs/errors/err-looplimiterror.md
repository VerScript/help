# LoopLimitError

**Category:** ERROR | **Subcategory:** Iteration

## Summary
Loop iterations exceeded max execution bound.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless LoopLimitError:
  display "Caught LoopLimitError" ?color=#f59e0b
```
