# include

**Category:** KEYWORD | **Subcategory:** Header Contracts

## Summary
Explicitly imports and binds an external *.h.vrs header contract specification into the current compilation unit.

## Syntax
```verscript
include "<path_to_header>.h.vrs"
```

## Description
Loads header prototypes and validates all function implementations against declared signatures.

## Parameters / Arguments
- `headerPath` *(string)*: Relative or absolute file path to the *.h.vrs file.

**Return Value / Type:** `void`

## Paired Keywords & Related Topics
`header`, `contract`, `import`, `load`

## Runnable Code Example
```verscript
include "math_contract.h.vrs"

def func add(a: num, b: num):
  reply a + b
```
