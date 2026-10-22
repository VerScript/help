# header

**Category:** KEYWORD | **Subcategory:** Header Contracts

## Summary
Defines an interface contract specification declaring prototypes and type constraints in *.h.vrs files.

## Syntax
```verscript
header <ContractName>:
  def func <routineName>(<params>): <return_type>
  struct <StructName>:
    <field> : <type>
```

## Description
Header specifications enforce compile-time and runtime contracts between callers and implementations. Companion headers (<file>.h.vrs) are automatically detected and verified against implementations (<file>.vrs).

## Parameters / Arguments
- `ContractName` *(identifier)*: Name of the header specification block.

**Return Value / Type:** `Contract Definition`

## Paired Keywords & Related Topics
`include`, `contract`, `require`, `ensure`, `struct`, `def`

## Runnable Code Example
```verscript
header MathSpec:
  def func add(a: num, b: num): num
  def func mul(a: num, b: num): num
```
