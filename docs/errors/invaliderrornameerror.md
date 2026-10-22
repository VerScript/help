# InvalidErrorNameError — Exception Type

> **Category**: `error` | **Subcategory**: Exception

## Overview
Suppression directive or throw passed an unregistered error name.

## Criticality & Suppression
- **Criticality Score**: 4 / 10
- **Suppression Tier**: Tier 1

### Common Trigger
Suppression directive or throw passed an unregistered error name.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless InvalidErrorNameError:
  display "Caught InvalidErrorNameError" ?color=#f59e0b
```

