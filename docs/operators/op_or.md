# || (Logical OR)

**Category:** OPERATOR | **Subcategory:** Logical

## Summary
Short-circuiting logical disjunction. Evaluates to true if either operand is truthy.

## Syntax
```verscript
<a> || <b>
```

## Description
If `a` is true, returns true immediately without evaluating `b`.

## Parameters / Arguments
- `a` *(bool)*: First condition.
- `b` *(bool)*: Second condition.

**Return Value / Type:** `bool`

## Paired Keywords & Related Topics
`&&`, `!`, `if`

## Runnable Code Example
```verscript
if cache.exists || fetchRemote() then:
  display "Data ready"
```
