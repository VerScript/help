# LoopDirectionError

**Category:** ERROR | **Subcategory:** Iteration

## Summary
Positive step specified for descending range (e.g. 10 to 0 by +1).

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless LoopDirectionError:
  display "Caught LoopDirectionError" ?color=#f59e0b
```
