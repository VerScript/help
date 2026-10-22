# SystemError — Exception Type

> **Category**: `error` | **Subcategory**: OS

## Overview
Native operating system call failure.

## Criticality & Suppression
- **Criticality Score**: 8 / 10
- **Suppression Tier**: Tier 3

### Common Trigger
Native operating system call failure.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless SystemError:
  display "Caught SystemError" ?color=#f59e0b
```

