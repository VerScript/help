# DataTypeError — Invariant Constraint Breach

> **Category**: `error` | **Subcategory**: Type System

## Overview
Raised when assigning a value to a DataType-annotated variable that violates the declared type or guard invariant.

## Criticality & Suppression
- **Criticality Score**: 6 / 10
- **Suppression Tier**: Tier 2 (CriticalErrors compatible)

### Common Trigger
Assigning string to num; violating guard predicate in custom DataType.

### Recommended Remedy
Ensure assigned values satisfy DataType guard conditions before assignment.

## Example
```verscript
DataType PositiveNum:
  val : num
  guard val > 0

do:
  set PositiveNum p : -5
unless DataTypeError:
  display "Validation caught negative value!" ?color=#ef4444
```

