# VisibilityError — Exception Type

> **Category**: `error` | **Subcategory**: OOP

## Overview
Accessing private member from outside enclosing scope.

## Criticality & Suppression
- **Criticality Score**: 5 / 10
- **Suppression Tier**: Tier 1

### Common Trigger
Accessing private member from outside enclosing scope.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless VisibilityError:
  display "Caught VisibilityError" ?color=#f59e0b
```

