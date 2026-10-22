# Reactive Events and Listeners

**Category:** FUNCTIONALITY | **Subcategory:** Reactive

## Summary
Publishing and subscribing to reactive events across the VerScript runtime without tight coupling.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
on "order:created", def(orderId):
  display "Notification sent for order #" + orderId ?color=#22c55e

emit "order:created", 45892
```
