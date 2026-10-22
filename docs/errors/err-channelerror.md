# ChannelError

**Category:** ERROR | **Subcategory:** Concurrency

## Summary
Writing to closed channel or buffer deadlock.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Risky code
  display "Running..."
unless ChannelError:
  display "Caught ChannelError" ?color=#f59e0b
```
