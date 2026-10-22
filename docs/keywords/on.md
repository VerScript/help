# on — Register Reactive Event Listener

> **Category**: `keyword` | **Subcategory**: Reactive & Event Architecture

## Overview
Attaches a callback procedure to listen for specific events fired via 'emit'.

## Syntax
```verscript
on <eventName>, <handler_procedure>
```

## Example
```verscript
on "payment:success", def(amount):
  display "Payment processed: $" + amount ?color=#22c55e

emit "payment:success", 450
```

