# match

**Category:** KEYWORD | **Subcategory:** Conditional Control Flow

## Summary
Tests a subject against multiple pattern branches with structural deconstruction and type matching.

## Syntax
```verscript
match <subject> with:
  case <pattern1>: <action1>
  case <pattern2>: <action2>
  case _: <default_action>
```

## Parameters / Arguments
- `subject` *(any)*: undefined
- `cases` *(pattern list)*: undefined

## Runnable Code Example
```verscript
set role : "admin"
match role with:
  case "admin": display "Full Root Permissions" ?color=#00FFCC
  case "user":  display "Standard Access" ?color=#38bdf8
  case _:       display "Guest Mode"
```
