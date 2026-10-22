# VisibilityError

**Category:** ERROR | **Subcategory:** OOP

## Summary
Accessing private member from outside enclosing scope.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless VisibilityError:
  display "Caught VisibilityError" ?color=#f59e0b
```
