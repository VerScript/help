# % (Modulo)

**Category:** OPERATOR | **Subcategory:** Arithmetic

## Summary
Calculates the integer or floating-point remainder of dividing two numbers.

## Syntax
```verscript
<a> % <b>
```

## Description
Computes remainder after division (e.g. 10 % 3 = 1). Essential for parity checks and circular buffer wrapping.

## Parameters / Arguments
- `a` *(num)*: Dividend.
- `b` *(num)*: Divisor.

**Return Value / Type:** `num`

## Paired Keywords & Related Topics
`/`, `Math`

## Runnable Code Example
```verscript
if count % 2 == 0 then:
  display "Even number"
else:
  display "Odd number"
```
