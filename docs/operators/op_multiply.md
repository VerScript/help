# * (Multiplication)

**Category:** OPERATOR | **Subcategory:** Arithmetic

## Summary
Multiplies two numeric factors, or repeats a string/array by an integer factor.

## Syntax
```verscript
<a> * <b>
```

## Description
Performs arithmetic multiplication: 6 * 7 = 42. When used with strings and numbers ("=" * 10), generates repeating sequences.

## Parameters / Arguments
- `a` *(num | str)*: Left multiplicand.
- `b` *(num)*: Right multiplicand.

**Return Value / Type:** `num | str`

## Paired Keywords & Related Topics
`/`, `+`, `-`

## Runnable Code Example
```verscript
set area : width * height
set line : "=" * 20
display line
```
