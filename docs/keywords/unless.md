# unless — Exception Interception Handler

> **Category**: `keyword` | **Subcategory**: Control Flow & Exception Shielding

## Overview
Pairs with 'do' to intercept specific or general errors, executing recovery procedures when an exception occurs.

## Syntax
```verscript
do:
  <body>
unless [ErrorName]:
  <fallback>
```

## Example
```verscript
do:
  set res : 50 / divisor
unless DivisionByZeroError:
  set res : 999999
  display "Divisor was zero, defaulted to max." ?color=#f59e0b
```

