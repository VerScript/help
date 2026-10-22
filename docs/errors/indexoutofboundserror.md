# IndexOutOfBoundsError — Exception Type

> **Category**: `error` | **Subcategory**: Array

## Overview
Index exceeds array bounds.

## Criticality & Suppression
- **Criticality Score**: 5 / 10
- **Suppression Tier**: Tier 1

### Common Trigger
Index exceeds array bounds.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless IndexOutOfBoundsError:
  display "Caught IndexOutOfBoundsError" ?color=#f59e0b
```

