# void

**Category:** DATATYPE | **Subcategory:** Function Signatures

## Summary
Designates that a routine performs side-effects and returns no meaningful value.

## Syntax
```verscript
def func <name>(<params>) -> void:
  <body>
```

## Description
Used primarily in header contract files (*.h.vrs) and explicit function signatures to indicate procedure calls that reply nothing.

**Return Value / Type:** `void`

## Paired Keywords & Related Topics
`def`, `func`, `reply`, `header`

## Runnable Code Example
```verscript
header LoggerContract:
  def func logMessage(msg: str) -> void

include "LoggerContract.h.vrs"
```
