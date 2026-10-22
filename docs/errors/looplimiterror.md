# LoopLimitError — Exception Type

> **Category**: `error` | **Subcategory**: Iteration

## Overview
Loop iterations exceeded max execution bound.

## Criticality & Suppression
- **Criticality Score**: 5 / 10
- **Suppression Tier**: Tier 1

### Common Trigger
Loop iterations exceeded max execution bound.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless LoopLimitError:
  display "Caught LoopLimitError" ?color=#f59e0b
```

