# DataType

**Category:** DATATYPE | **Subcategory:** Constrained Types

## Summary
Defines a custom named datatype with runtime validation constraints and invariant predicates.

## Syntax
```verscript
DataType <TypeName>:
  guard <expression_with_it>

DataType <Port>:
  guard it >= 1 && it <= 65535
```

## Description
The `DataType` construct enables domain-driven type invariants. Any assignment to a variable annotated with this type verifies the `guard` rule against `it` and throws `DataTypeError` upon violation.

## Parameters / Arguments
- `TypeName` *(identifier)*: Name of the constrained custom type.
- `guard` *(boolean expression using it)*: Validation invariant.

**Return Value / Type:** `DataType`

## Paired Keywords & Related Topics
`guard`, `it`, `set`, `throw`

## Runnable Code Example
```verscript
DataType PositiveNum:
  guard it > 0

set PositiveNum count : 5
! set PositiveNum err : -1  (Throws DataTypeError)
```
