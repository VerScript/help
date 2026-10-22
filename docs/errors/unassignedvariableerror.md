# UnassignedVariableError — Exception Type

> **Category**: `error` | **Subcategory**: Scope

## Overview
Reading variable declared without initialization.

## Criticality & Suppression
- **Criticality Score**: 4 / 10
- **Suppression Tier**: Tier 1

### Common Trigger
Reading variable declared without initialization.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless UnassignedVariableError:
  display "Caught UnassignedVariableError" ?color=#f59e0b
```

