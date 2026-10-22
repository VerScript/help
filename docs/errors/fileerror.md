# FileError — Exception Type

> **Category**: `error` | **Subcategory**: I/O

## Overview
File not found or permission denied during Fs operations.

## Criticality & Suppression
- **Criticality Score**: 6 / 10
- **Suppression Tier**: Tier 2

### Common Trigger
File not found or permission denied during Fs operations.

### Recommended Remedy
Use do...unless blocks or validate inputs prior to invocation.

## Example
```verscript
do:
  ! Risky code
  display "Running..."
unless FileError:
  display "Caught FileError" ?color=#f59e0b
```

