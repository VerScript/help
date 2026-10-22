# InvalidErrorNameError

**Category:** ERROR | **Subcategory:** Exception

## Summary
Suppression directive or throw passed an unregistered error name.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless InvalidErrorNameError:
  display "Caught InvalidErrorNameError" ?color=#f59e0b
```
