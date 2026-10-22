# throw — Raise Custom Exception

> **Category**: `keyword` | **Subcategory**: Control Flow & Exception Shielding

## Overview
Explicitly raises a named exception or custom error, interrupting standard execution and transferring control to an enclosing 'unless' block.

## Syntax
```verscript
throw <ErrorName> ["Error message description"]
```

## Example
```verscript
def requirePositive(n):
  if n <= 0 then throw DomainError "Value must be positive"
  reply n
```

