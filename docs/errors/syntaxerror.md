# SyntaxError — Exception Type

> **Category**: `error` | **Subcategory**: Parser

## Overview
Invalid token stream or missing required delimiter.

## Criticality & Suppression
- **Criticality Score**: 7 / 10
- **Suppression Tier**: Tier 3

### Common Trigger
Invalid token stream or missing required delimiter.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless SyntaxError:
  display "Caught SyntaxError" ?color=#f59e0b
```

