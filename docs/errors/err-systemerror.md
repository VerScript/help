# SystemError

**Category:** ERROR | **Subcategory:** OS

## Summary
Native operating system call failure.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless SystemError:
  display "Caught SystemError" ?color=#f59e0b
```
