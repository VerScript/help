# == (Equality)

**Category:** OPERATOR | **Subcategory:** Comparison

## Summary
Tests whether two expressions have equal values across numbers, strings, booleans, and arrays.

## Syntax
```verscript
<a> == <b>
```

## Description
Returns true if values are identical; supports structural comparison of strings and numbers.

## Parameters / Arguments
- `a` *(any)*: Left operand.
- `b` *(any)*: Right operand.

**Return Value / Type:** `bool`

## Paired Keywords & Related Topics
`!=`, `<`, `>`, `<=`, `>=`

## Runnable Code Example
```verscript
if status == "ready" then:
  display "Proceeding"
```
