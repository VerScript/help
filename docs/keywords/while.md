# while — VerScript Language Keyword

> **Category**: `keyword` | **Subcategory**: Iteration

## Overview
Executes a block continuously as long as the condition evaluates to true.

## Syntax
```verscript
while <condition>:
  <body>
```

## Example
```verscript
set i : 0
while i < 5:
  display i
  set i : i + 1
```

