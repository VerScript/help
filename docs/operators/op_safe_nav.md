# ?. (Safe Navigation)

**Category:** OPERATOR | **Subcategory:** Member Access

## Summary
Safe property or method navigation; returns nil without throwing an error if the receiver is nil.

## Syntax
```verscript
<receiver>?.<property>
<receiver>?.<method>(<args>)
```

## Description
Prevents NullPointer / UndefinedVariable errors when traversing deeply nested optional structures.

## Parameters / Arguments
- `receiver` *(entity | object | nil)*: Object to traverse.

**Return Value / Type:** `any or nil`

## Paired Keywords & Related Topics
`??`, `nil`, `.`

## Runnable Code Example
```verscript
set city : user?.profile?.address?.city ?? "Unknown City"
display city
```
