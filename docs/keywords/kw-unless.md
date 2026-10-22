# unless

**Category:** KEYWORD | **Subcategory:** Control Flow & Exception Shielding

## Summary
Pairs with 'do' to intercept specific or general errors, executing recovery procedures when an exception occurs.

## Syntax
```verscript
do:
  <body>
unless [ErrorName]:
  <fallback>
```

## Parameters / Arguments
- `ErrorName (optional)` *(identifier)*: undefined

## Runnable Code Example
```verscript
do:
  set res : 50 / divisor
unless DivisionByZeroError:
  set res : 999999
  display "Divisor was zero, defaulted to max." ?color=#f59e0b
```
