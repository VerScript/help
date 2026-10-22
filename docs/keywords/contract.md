# contract

**Category:** KEYWORD | **Subcategory:** Header Contracts

## Summary
Declares an invariant behavioral specification for functions, structs, or libraries.

## Syntax
```verscript
contract <Name>:
  require: <precondition>
  ensure: <postcondition>
```

## Description
Enforces Design by Contract (DbC). Contracts guarantee preconditions before routines execute and postconditions after return.

## Parameters / Arguments
- `Name` *(identifier)*: Name of the contract specification.

**Return Value / Type:** `Contract Block`

## Paired Keywords & Related Topics
`header`, `require`, `ensure`, `inbound`, `outbound`

## Runnable Code Example
```verscript
contract SafeDivision:
  require: denominator != 0
  ensure: it != nil
```
