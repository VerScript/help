# emit

**Category:** KEYWORD | **Subcategory:** Reactive & Event Architecture

## Summary
Fires an event into the global or scoped reactive bus, immediately triggering all matching 'on' listeners.

## Syntax
```verscript
emit <eventName> [, <payload>]
```

## Parameters / Arguments
- `eventName` *(str)*: undefined
- `payload (optional)` *(any)*: undefined

## Runnable Code Example
```verscript
on "telemetry:alert", def(data):
  display "ALERT: " + data ?color=#ef4444

emit "telemetry:alert", "Overheating in core 3"
```
