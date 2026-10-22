# ! (Logical NOT / Comment Prefix)

**Category:** OPERATOR | **Subcategory:** Logical & Comments

## Summary
Logical negation operator in expressions (!expr); also line comment prefix when starting a line (! comment).

## Syntax
```verscript
!<expression>
! Single line comment
```

## Description
Dual functionality in VerScript: (1) Inside expressions: inverts boolean truthiness (!true == false), (2) At start of line: denotes a line comment.

## Parameters / Arguments
- `expr` *(bool or expression)*: Expression to negate.

**Return Value / Type:** `bool`

## Paired Keywords & Related Topics
`&&`, `||`, `unless`

## Runnable Code Example
```verscript
! This is a VerScript comment line
set bool flag : false
if !flag then:
  display "Flag was false"
```
