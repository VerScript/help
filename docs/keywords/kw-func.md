# func

**Category:** KEYWORD | **Subcategory:** Procedures & Functions

## Summary
Enforces deterministic pure function semantics: zero global side effects, referential transparency, and deterministic outputs.

## Syntax
```verscript
func <name> ( [arg1, arg2, ...] ):
  <body>
  reply <value>
```

## Parameters / Arguments
- `name` *(identifier)*: undefined
- `arguments` *(list)*: undefined

## Runnable Code Example
```verscript
func factorial(n):
  if n <= 1 then reply 1
  reply n * factorial(n - 1)

display "5! = " + factorial(5) ?color=#22c55e
```
