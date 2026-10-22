# How to Build Event-Driven Architecture with emit and on

> **Category**: `functionality` | **Subcategory**: Reactive

## Overview
Publishing and subscribing to reactive events across the VerScript runtime without tight coupling.

## Example
```verscript
on "order:created", def(orderId):
  display "Notification sent for order #" + orderId ?color=#22c55e

emit "order:created", 45892
```

