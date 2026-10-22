# FileError

**Category:** ERROR | **Subcategory:** I/O

## Summary
File not found or permission denied during Fs operations.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless FileError:
  display "Caught FileError" ?color=#f59e0b
```
