# MatchError

**Category:** ERROR | **Subcategory:** Control

## Summary
No match branch satisfied and no default case (_) provided.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless MatchError:
  display "Caught MatchError" ?color=#f59e0b
```
