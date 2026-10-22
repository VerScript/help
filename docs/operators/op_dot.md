# . (Member Access)

**Category:** OPERATOR | **Subcategory:** Member Access

## Summary
Accesses a property or invokes a method on an entity, library, string, or array instance.

## Syntax
```verscript
<object>.<member>
```

## Description
Standard dot-operator notation for object-oriented dispatch, library routine calls (Matrix.det), and property reading.

## Parameters / Arguments
- `object` *(entity | lib | str | arr)*: Receiver instance.
- `member` *(identifier)*: Property or method name.

**Return Value / Type:** `any`

## Paired Keywords & Related Topics
`?.`, `this`, `class`, `lib`

## Runnable Code Example
```verscript
load Math
set radius : 5
set circ : 2 * Math.PI * radius
```
