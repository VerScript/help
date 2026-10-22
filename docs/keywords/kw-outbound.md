# outbound

**Category:** KEYWORD | **Subcategory:** Interface Contracts

## Summary
Enforces postconditions and return value contracts on function exit.

## Syntax
```verscript
outbound: <return_guard>
```

## Runnable Code Example
```verscript
def getPositive():
  outbound: it > 0
  reply 42
```
