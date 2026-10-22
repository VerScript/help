# - (Subtraction / Negation)

**Category:** OPERATOR | **Subcategory:** Arithmetic

## Summary
Subtracts the right numeric operand from the left operand, or negates a numeric expression as unary minus.

## Syntax
```verscript
<a> - <b>
-<expression>
```

## Description
Binary subtraction (e.g. 10 - 4 = 6) and unary negation (e.g. -x).

## Parameters / Arguments
- `a` *(num)*: Minuend.
- `b` *(num)*: Subtrahend.

**Return Value / Type:** `num`

## Paired Keywords & Related Topics
`+`, `*`, `/`

## Runnable Code Example
```verscript
set diff : 100 - 35
set inv : -diff
display inv
```
