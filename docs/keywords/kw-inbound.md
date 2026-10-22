# inbound

**Category:** KEYWORD | **Subcategory:** Interface Contracts

## Summary
Enforces input parameter validation and preconditions on a function entry.

## Syntax
```verscript
inbound: <validation_guard>
```

## Runnable Code Example
```verscript
def divide(a, b):
  inbound: b != 0
  reply a / b
```
