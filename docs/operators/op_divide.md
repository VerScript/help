# / (Division)

**Category:** OPERATOR | **Subcategory:** Arithmetic

## Summary
Divides the left numeric operand by the right operand. Throws DivisionByZeroError if denominator is 0.

## Syntax
```verscript
<a> / <b>
```

## Description
Floating point division. Automatically throws `DivisionByZeroError` if the denominator equals 0.

## Parameters / Arguments
- `a` *(num)*: Dividend.
- `b` *(num (non-zero))*: Divisor.

**Return Value / Type:** `num`

## Paired Keywords & Related Topics
`%`, `*`, `+`

## Runnable Code Example
```verscript
set ratio : 100 / 4
display "Ratio: " + ratio
```
