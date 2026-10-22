# <, >, <=, >= (Relational)

**Category:** OPERATOR | **Subcategory:** Comparison

## Summary
Ordered relational comparisons: less than (<), greater than (>), less/equal (<=), greater/equal (>=).

## Syntax
```verscript
<a> < <b>
<a> > <b>
<a> <= <b>
<a> >= <b>
```

## Description
Evaluates numerical order and lexicographical string order.

## Parameters / Arguments
- `a` *(num | str)*: Left operand.
- `b` *(num | str)*: Right operand.

**Return Value / Type:** `bool`

## Paired Keywords & Related Topics
`==`, `!=`, `if`, `while`

## Runnable Code Example
```verscript
if age >= 18 then:
  display "Adult"
```
