# RuntimeError

**Category:** ERROR | **Subcategory:** Execution

## Summary
Generic runtime exception during expression evaluation.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless RuntimeError:
  display "Caught RuntimeError" ?color=#f59e0b
```
