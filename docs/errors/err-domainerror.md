# DomainError

**Category:** ERROR | **Subcategory:** Math

## Summary
Math function domain violation (e.g. sqrt of negative number).

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless DomainError:
  display "Caught DomainError" ?color=#f59e0b
```
