# ScopeViolationError — Scope or Purity Boundary Breach

> **Category**: `error` | **Subcategory**: Purity & Architecture

## Overview
Raised when pure functions (func) attempt to mutate external variables or access private/unscoped identifiers.

## Criticality & Suppression
- **Criticality Score**: 7 / 10
- **Suppression Tier**: Tier 3 (Scoped Suppression)

### Common Trigger
Mutating outer scope from inside a pure 'func' or accessing 'private' members externally.

### Recommended Remedy
Keep pure functions referentially transparent, or switch to 'def' for procedures with side effects.

## Example
```verscript
set globalCount : 0
! Inside func, modifying globalCount raises ScopeViolationError
```

