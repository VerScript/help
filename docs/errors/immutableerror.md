# ImmutableError — Exception Type

> **Category**: `error` | **Subcategory**: Storage

## Overview
Attempting to reassign a const variable.

## Criticality & Suppression
- **Criticality Score**: 6 / 10
- **Suppression Tier**: Tier 2

### Common Trigger
Attempting to reassign a const variable.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless ImmutableError:
  display "Caught ImmutableError" ?color=#f59e0b
```

