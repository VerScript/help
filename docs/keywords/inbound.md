# inbound — VerScript Language Keyword

> **Category**: `keyword` | **Subcategory**: Interface Contracts

## Overview
Enforces input parameter validation and preconditions on a function entry.

## Syntax
```verscript
inbound: <validation_guard>
```

## Example
```verscript
def divide(a, b):
  inbound: b != 0
  reply a / b
```

