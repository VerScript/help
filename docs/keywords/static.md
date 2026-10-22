# static — VerScript Language Keyword

> **Category**: `keyword` | **Subcategory**: Scope & Storage

## Overview
Preserves variable value across procedure invocations, or scopes to class namespace.

## Syntax
```verscript
static <var> : <val>
```

## Example
```verscript
class MathUtil:
  static: def add(a, b): reply a + b
```

