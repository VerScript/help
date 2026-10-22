# DomainError — Exception Type

> **Category**: `error` | **Subcategory**: Math

## Overview
Math function domain violation (e.g. sqrt of negative number).

## Criticality & Suppression
- **Criticality Score**: 5 / 10
- **Suppression Tier**: Tier 1

### Common Trigger
Math function domain violation (e.g. sqrt of negative number).

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless DomainError:
  display "Caught DomainError" ?color=#f59e0b
```

