# do — Scoped Execution & Exception Shield

> **Category**: `keyword` | **Subcategory**: Control Flow & Exception Shielding

## Overview
Creates a protected execution block. When paired with 'unless', provides robust try/catch-style exception shielding against runtime errors.

## Syntax
```verscript
do:
  <guarded code>
unless <ErrorName>:
  <recovery code>
```

## Example
```verscript
do:
  load Matrix
  set inv : Matrix.inv([[1, 2], [2, 4]])
unless SystemError:
  display "Singular matrix detected; fallback to pseudo-inverse." ?color=#ef4444
```

