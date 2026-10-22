# AssertError — Exception Type

> **Category**: `error` | **Subcategory**: Guard

## Overview
Guard condition or assert evaluated to false.

## Criticality & Suppression
- **Criticality Score**: 7 / 10
- **Suppression Tier**: Tier 3

### Common Trigger
Guard condition or assert evaluated to false.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless AssertError:
  display "Caught AssertError" ?color=#f59e0b
```

