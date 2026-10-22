# RuntimeError — Exception Type

> **Category**: `error` | **Subcategory**: Execution

## Overview
Generic runtime exception during expression evaluation.

## Criticality & Suppression
- **Criticality Score**: 6 / 10
- **Suppression Tier**: Tier 2

### Common Trigger
Generic runtime exception during expression evaluation.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless RuntimeError:
  display "Caught RuntimeError" ?color=#f59e0b
```

