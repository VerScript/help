# outscope — VerScript Language Keyword

> **Category**: `keyword` | **Subcategory**: Scope Escapes

## Overview
Binds a value in the parent lexical scope from within a nested block.

## Syntax
```verscript
outscope <var> : <val>
```

## Example
```verscript
do:
  outscope leakedVar : 100
```

