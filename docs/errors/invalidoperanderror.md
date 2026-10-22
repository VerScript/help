# InvalidOperandError — Exception Type

> **Category**: `error` | **Subcategory**: Expression

## Overview
Applying an operator to incompatible types (e.g. adding boolean to array).

## Criticality & Suppression
- **Criticality Score**: 4 / 10
- **Suppression Tier**: Tier 1

### Common Trigger
Applying an operator to incompatible types (e.g. adding boolean to array).

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless InvalidOperandError:
  display "Caught InvalidOperandError" ?color=#f59e0b
```

