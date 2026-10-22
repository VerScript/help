# != (Inequality)

**Category:** OPERATOR | **Subcategory:** Comparison

## Summary
Tests whether two expressions evaluate to different values.

## Syntax
```verscript
<a> != <b>
```

## Description
Inverted equality test. Returns true when `a` is not equal to `b`.

## Parameters / Arguments
- `a` *(any)*: Left operand.
- `b` *(any)*: Right operand.

**Return Value / Type:** `bool`

## Paired Keywords & Related Topics
`==`, `!`, `if`

## Runnable Code Example
```verscript
if token != nil then:
  display "Authenticated"
```
