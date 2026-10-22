# LoopStepError — Exception Type

> **Category**: `error` | **Subcategory**: Iteration

## Overview
Step of 0 passed to range loop.

## Criticality & Suppression
- **Criticality Score**: 4 / 10
- **Suppression Tier**: Tier 1

### Common Trigger
Step of 0 passed to range loop.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless LoopStepError:
  display "Caught LoopStepError" ?color=#f59e0b
```

