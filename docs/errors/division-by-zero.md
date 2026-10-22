# DivisionByZeroError — Divide or Modulo by Zero

> **Category**: `error` | **Subcategory**: Arithmetic

## Overview
Triggered whenever an arithmetic division (/) or remainder (%) operation receives a zero denominator.

## Criticality & Suppression
- **Criticality Score**: 5 / 10
- **Suppression Tier**: Tier 1 (SuppressErrors compatible)

### Common Trigger
Dividing a numeric value by 0 or 0.0.

### Recommended Remedy
Guard divisors with an if check or enclose within a do...unless DivisionByZeroError block.

## Example
```verscript
do:
  set res : 100 / divisor
unless DivisionByZeroError:
  display "Cannot divide by zero!" ?color=#f59e0b
  set res : 0
```

