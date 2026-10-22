# guard

**Category:** KEYWORD | **Subcategory:** Control Flow & Watchguards

## Summary
Establishes a reactive watchguard that monitors an invariant expression, immediately triggering alerts if violated.

## Syntax
```verscript
guard <condition>:
  <alert_action>
```

## Parameters / Arguments
- `condition` *(bool)*: undefined

## Runnable Code Example
```verscript
set num balance : 500
guard balance >= 0:
  display "Violation: Balance cannot be negative!" ?color=#ef4444
set balance : balance - 100
```
