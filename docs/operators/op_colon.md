# : (Assignment & Block Colon)

**Category:** OPERATOR | **Subcategory:** Syntax & Assignment

## Summary
Binds values to variables (set x: 42) and marks indented block headers (if cond:, loop 5:).

## Syntax
```verscript
set <var> : <value>
<keyword> <condition>:
  <indented_body>
```

## Description
The fundamental syntactic pillar of VerScript: (1) Replaces the equal sign `=` for variable assignments, (2) Introduces Python-style indented blocks.

**Return Value / Type:** `void`

## Paired Keywords & Related Topics
`set`, `def`, `if`, `while`, `class`, `lib`

## Runnable Code Example
```verscript
set x : 100
if x > 50:
  display "Greater than 50"
```
