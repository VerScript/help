# AsyncError

**Category:** ERROR | **Subcategory:** Concurrency

## Summary
Unhandled panic inside async worker fiber.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless AsyncError:
  display "Caught AsyncError" ?color=#f59e0b
```
