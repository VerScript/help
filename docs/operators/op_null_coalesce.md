# ?? (Nullish Coalescing)

**Category:** OPERATOR | **Subcategory:** Fallbacks

## Summary
Returns the right-hand operand if the left operand is nil or empty, otherwise returns the left operand.

## Syntax
```verscript
<expr> ?? <default_value>
```

## Description
Provides a robust fallback mechanism for optional or uninitialized variables.

## Parameters / Arguments
- `expr` *(any)*: Primary value.
- `default_value` *(any)*: Fallback value if expr is nil.

**Return Value / Type:** `any`

## Paired Keywords & Related Topics
`?.`, `nil`, `set`

## Runnable Code Example
```verscript
set port : config.port ?? 8080
display "Running on port: " + port
```
