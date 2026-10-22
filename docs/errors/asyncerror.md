# AsyncError — Exception Type

> **Category**: `error` | **Subcategory**: Concurrency

## Overview
Unhandled panic inside async worker fiber.

## Criticality & Suppression
- **Criticality Score**: 7 / 10
- **Suppression Tier**: Tier 3

### Common Trigger
Unhandled panic inside async worker fiber.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless AsyncError:
  display "Caught AsyncError" ?color=#f59e0b
```

