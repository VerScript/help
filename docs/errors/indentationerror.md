# IndentationError — Exception Type

> **Category**: `error` | **Subcategory**: Syntax

## Overview
Mismatched indentation spacing across block boundaries.

## Criticality & Suppression
- **Criticality Score**: 6 / 10
- **Suppression Tier**: Tier 2

### Common Trigger
Mismatched indentation spacing across block boundaries.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless IndentationError:
  display "Caught IndentationError" ?color=#f59e0b
```

