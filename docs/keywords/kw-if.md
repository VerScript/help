# if

**Category:** KEYWORD | **Subcategory:** Conditional Control Flow

## Summary
Evaluates a boolean condition, executing the 'then' block if true, or the optional 'else' block if false.

## Syntax
```verscript
if <condition> then
  <consequent>
[else
  <alternative>]
```

## Parameters / Arguments
- `condition` *(bool)*: undefined

## Runnable Code Example
```verscript
set speed : 120
if speed > 100 then
  display "ALERT: Speed limit exceeded!" ?color=#ef4444
else
  display "Speed within normal parameters." ?color=#22c55e
```
