# any

**Category:** DATATYPE | **Subcategory:** Variant Type

## Summary
Unconstrained polymorphic variant type bypassing strict compile-time type validation.

## Syntax
```verscript
set any <name> : <value>
```

## Description
The `any` datatype allows a variable to hold any value (num, str, bool, arr, entity) and be dynamically reassigned to other types at runtime without triggering a DataTypeError.

## Parameters / Arguments
- `value` *(any expression)*: Any valid VerScript expression.

**Return Value / Type:** `any`

## Paired Keywords & Related Topics
`DataType`, `as`, `set`

## Runnable Code Example
```verscript
set any dynamicVal : 42
set dynamicVal : "Now I am a string"
display dynamicVal
```
