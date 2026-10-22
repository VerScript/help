# SyntaxError

**Category:** ERROR | **Subcategory:** Parser

## Summary
Invalid token stream or missing required delimiter.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless SyntaxError:
  display "Caught SyntaxError" ?color=#f59e0b
```
