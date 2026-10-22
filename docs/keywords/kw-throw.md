# throw

**Category:** KEYWORD | **Subcategory:** Control Flow & Exception Shielding

## Summary
Explicitly raises a named exception or custom error, interrupting standard execution and transferring control to an enclosing 'unless' block.

## Syntax
```verscript
throw <ErrorName> ["Error message description"]
```

## Parameters / Arguments
- `ErrorName` *(identifier)*: undefined
- `message (optional)` *(str)*: undefined

## Runnable Code Example
```verscript
def requirePositive(n):
  if n <= 0 then throw DomainError "Value must be positive"
  reply n
```
