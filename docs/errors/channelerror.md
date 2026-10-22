# ChannelError — Exception Type

> **Category**: `error` | **Subcategory**: Concurrency

## Overview
Writing to closed channel or buffer deadlock.

## Criticality & Suppression
- **Criticality Score**: 6 / 10
- **Suppression Tier**: Tier 2

### Common Trigger
Writing to closed channel or buffer deadlock.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless ChannelError:
  display "Caught ChannelError" ?color=#f59e0b
```

