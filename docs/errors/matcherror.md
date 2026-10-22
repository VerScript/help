# MatchError — Exception Type

> **Category**: `error` | **Subcategory**: Control

## Overview
No match branch satisfied and no default case (_) provided.

## Criticality & Suppression
- **Criticality Score**: 5 / 10
- **Suppression Tier**: Tier 1

### Common Trigger
No match branch satisfied and no default case (_) provided.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless MatchError:
  display "Caught MatchError" ?color=#f59e0b
```

