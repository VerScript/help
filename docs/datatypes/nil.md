# nil

**Category:** DATATYPE | **Subcategory:** Literals

## Summary
Represents the intentional absence of any value or uninitialized object reference.

## Syntax
```verscript
set <name> : nil
if <name> == nil then: ...
```

## Description
`nil` (or `null`) represents null pointers and absent values. Safe navigation `?.` and nullish coalescing `??` operators are designed specifically to handle `nil` references safely.

**Return Value / Type:** `nil`

## Paired Keywords & Related Topics
`null`, `??`, `?.`, `if`

## Runnable Code Example
```verscript
set user : nil
set name : user?.name ?? "Anonymous"
display name
```
