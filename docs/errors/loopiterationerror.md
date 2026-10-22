# LoopIterationError — Exception Type

> **Category**: `error` | **Subcategory**: Iteration

## Overview
Invalid iteration parameters or modifying collection while iterating.

## Criticality & Suppression
- **Criticality Score**: 4 / 10
- **Suppression Tier**: Tier 1

### Common Trigger
Invalid iteration parameters or modifying collection while iterating.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless LoopIterationError:
  display "Caught LoopIterationError" ?color=#f59e0b
```

