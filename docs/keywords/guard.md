# guard — Memory & Invariant Watchguard

> **Category**: `keyword` | **Subcategory**: Control Flow & Watchguards

## Overview
Establishes a reactive watchguard that monitors an invariant expression, immediately triggering alerts if violated.

## Syntax
```verscript
guard <condition>:
  <alert_action>
```

## Example
```verscript
set num balance : 500
guard balance >= 0:
  display "Violation: Balance cannot be negative!" ?color=#ef4444
set balance : balance - 100
```

