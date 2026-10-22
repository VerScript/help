# bool

**Category:** DATATYPE | **Subcategory:** Primitive Types

## Summary
Boolean truth flag literal accepting either true or false.

## Syntax
```verscript
set bool <name> : true | false
```

## Description
Used across all conditional control flow branches (if, unless, while, until, match). Boolean expressions evaluate comparison operations (==, !=, <, >, <=, >=) and logical combinations (&&, ||, !).

## Parameters / Arguments
- `value` *(boolean)*: Keyword true or false.

**Return Value / Type:** `bool`

## Paired Keywords & Related Topics
`if`, `while`, `until`, `unless`, `guard`

## Runnable Code Example
```verscript
set bool active : true
if active then:
  display "System is online!" ?color=green
```
