# DataTypeError

**Category:** ERROR | **Subcategory:** Type System

## Summary
Raised when assigning a value to a DataType-annotated variable that violates the declared type or guard invariant.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
DataType PositiveNum:
  val : num
  guard val > 0

do:
  set PositiveNum p : -5
unless DataTypeError:
  display "Validation caught negative value!" ?color=#ef4444
```
