# && (Logical AND)

**Category:** OPERATOR | **Subcategory:** Logical

## Summary
Short-circuiting logical conjunction. Evaluates to true only if both operands are truthy.

## Syntax
```verscript
<a> && <b>
```

## Description
If `a` evaluates to false, `b` is short-circuited and not evaluated.

## Parameters / Arguments
- `a` *(bool)*: First condition.
- `b` *(bool)*: Second condition.

**Return Value / Type:** `bool`

## Paired Keywords & Related Topics
`||`, `!`, `if`

## Runnable Code Example
```verscript
if user.isLoggedIn && user.hasPermission then:
  display "Access Granted"
```
