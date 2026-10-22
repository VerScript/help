# outbound — VerScript Language Keyword

> **Category**: `keyword` | **Subcategory**: Interface Contracts

## Overview
Enforces postconditions and return value contracts on function exit.

## Syntax
```verscript
outbound: <return_guard>
```

## Example
```verscript
def getPositive():
  outbound: it > 0
  reply 42
```

