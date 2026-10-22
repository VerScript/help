# on

**Category:** KEYWORD | **Subcategory:** Reactive & Event Architecture

## Summary
Attaches a callback procedure to listen for specific events fired via 'emit'.

## Syntax
```verscript
on <eventName>, <handler_procedure>
```

## Parameters / Arguments
- `eventName` *(str)*: undefined
- `handler` *(procedure)*: undefined

## Runnable Code Example
```verscript
on "payment:success", def(amount):
  display "Payment processed: $" + amount ?color=#22c55e

emit "payment:success", 450
```
