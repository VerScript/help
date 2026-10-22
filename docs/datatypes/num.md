# num

**Category:** DATATYPE | **Subcategory:** Primitive Types

## Summary
64-bit IEEE 754 double-precision floating point numeric value, representing integers and decimals seamlessly.

## Syntax
```verscript
set num <name> : <numeric_literal>
str a : "42"
set num parsed : a as num
```

## Description
The `num` type in VerScript represents both integer and fractional floating point values. It supports standard arithmetic operators (+, -, *, /, %), bitwise operations, mathematical functions in the Math library, and automatic type inference.

## Parameters / Arguments
- `literal` *(integer or float)*: Any decimal representation, e.g. 42, -10, 3.14159, 1e-4.

**Return Value / Type:** `num`

## Paired Keywords & Related Topics
`DataType`, `as`, `set`, `Math`

## Runnable Code Example
```verscript
set num count : 10
set num price : 19.99
set num total : count * price
display "Total: " + total ?color=cyan
```
