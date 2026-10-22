# LoopDirectionError — Exception Type

> **Category**: `error` | **Subcategory**: Iteration

## Overview
Positive step specified for descending range (e.g. 10 to 0 by +1).

## Criticality & Suppression
- **Criticality Score**: 4 / 10
- **Suppression Tier**: Tier 1

### Common Trigger
Positive step specified for descending range (e.g. 10 to 0 by +1).

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless LoopDirectionError:
  display "Caught LoopDirectionError" ?color=#f59e0b
```

