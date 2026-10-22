# emit — Dispatch Reactive Event

> **Category**: `keyword` | **Subcategory**: Reactive & Event Architecture

## Overview
Fires an event into the global or scoped reactive bus, immediately triggering all matching 'on' listeners.

## Syntax
```verscript
emit <eventName> [, <payload>]
```

## Example
```verscript
on "telemetry:alert", def(data):
  display "ALERT: " + data ?color=#ef4444

emit "telemetry:alert", "Overheating in core 3"
```

