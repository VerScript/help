# Json

**Category:** LIBRARY | **Subcategory:** Standard Library (Data)

## Summary
Converts VerScript arrays and entity objects to standard JSON strings, and parses JSON strings into native data structures.

## Syntax
```verscript
load Json
Json.stringify(obj [, pretty])
Json.parse(jsonString)
```

## Parameters / Arguments
- `data` *(any)*: undefined

## Runnable Code Example
```verscript
load Json
set user : { id: 1, name: "Ada Lovelace", verified: true }
set jsonStr : Json.stringify(user)
display jsonStr ?color=#00FFCC
```
