# AssertError

**Category:** ERROR | **Subcategory:** Guard

## Summary
Guard condition or assert evaluated to false.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless AssertError:
  display "Caught AssertError" ?color=#f59e0b
```
