# str

**Category:** DATATYPE | **Subcategory:** Primitive Types

## Summary
UTF-8 encoded string sequence with built-in string methods (.length, .substring, .toUpper, etc.).

## Syntax
```verscript
set str <name> : "string content"
str multiline : "Line 1\nLine 2"
```

## Description
VerScript strings are immutable UTF-8 text sequences. They support dynamic concatenation with the `+` operator, indexing, slicing, safe navigation, and rich methods such as `.split()`, `.trim()`, `.replace()`, and `.indexOf()`.

## Parameters / Arguments
- `literal` *(text sequence)*: Double-quoted string with escape sequences (\n, \t, \", \\).

**Return Value / Type:** `str`

## Paired Keywords & Related Topics
`display`, `prompt`, `as`, `String`

## Runnable Code Example
```verscript
set str name : "VerScript"
set str greeting : "Hello " + name
display greeting.toUpper()
```
