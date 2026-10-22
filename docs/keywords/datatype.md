# DataType — Constrained Custom Types

> **Category**: `keyword` | **Subcategory**: Type System & Schema

## Overview
Declares a formal user-defined type with validation constraints, invariant bounds, and schema contracts.

## Syntax
```verscript
DataType <TypeName>:
  <field1> : <type>
  [guard <constraint>]
```

## Example
```verscript
DataType UserProfile:
  username : str
  age : num
  guard age >= 18

set UserProfile admin : { username: "root", age: 32 }
```

