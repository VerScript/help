# set — Variable Assignment and Declaration

> **Category**: `keyword` | **Subcategory**: Declaration & Assignment

## Overview
Binds an identifier to a computed expression, literal value, or data structure. Supports type annotations, immutable constraints, and reactive bindings.

## Syntax
```verscript
set <identifier> : <expression>
set <type> <identifier> : <expression>
set const <identifier> : <expression>
```

## Example
```verscript
set num initialBalance : 500
set num deposit : 150
set num total : initialBalance + deposit
display "Total Account Balance: $" + total ?color=#22c55e
```

