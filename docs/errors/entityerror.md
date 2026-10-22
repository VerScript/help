# EntityError — Exception Type

> **Category**: `error` | **Subcategory**: Object

## Overview
Invalid property access or mutation on entity.

## Criticality & Suppression
- **Criticality Score**: 5 / 10
- **Suppression Tier**: Tier 1

### Common Trigger
Invalid property access or mutation on entity.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless EntityError:
  display "Caught EntityError" ?color=#f59e0b
```

