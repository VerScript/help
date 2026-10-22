# UndefinedVariableError — Unbound Identifier Read

> **Category**: `error` | **Subcategory**: Scope & Resolution

## Overview
Raised when accessing an identifier that has not been declared with 'set', 'def', or passed as an argument in the current scope.

## Criticality & Suppression
- **Criticality Score**: 3 / 10
- **Suppression Tier**: Tier 1 (SuppressErrors compatible)

### Common Trigger
Typo in variable name; accessing a variable outside the block where it was declared.

### Recommended Remedy
Declare variables before reading, check scope boundaries, and review variable spelling.

## Example
```verscript
do:
  set val : missingVar
unless UndefinedVariableError:
  display "Variable was not defined; fallback activated." ?color=#f59e0b
```

