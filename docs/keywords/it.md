# it — VerScript Language Keyword

> **Category**: `keyword` | **Subcategory**: Pipeline & Implicit Receiver

## Overview
Implicit receiver representing the pipelined input in pipeline expressions (|>) or postconditions.

## Syntax
```verscript
<expr> |> <op it>
```

## Example
```verscript
[1, 2, 3] |> it.length
```

