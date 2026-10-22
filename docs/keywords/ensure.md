# ensure

**Category:** KEYWORD | **Subcategory:** Header Contracts

## Summary
Specifies a postcondition predicate that must evaluate to true after routine completion before returning to caller.

## Syntax
```verscript
ensure: <boolean_condition_using_it>
```

## Description
Validates return values (accessible via `it`) and state postconditions. A false condition raises `PostconditionViolationError`.

## Parameters / Arguments
- `condition` *(bool expression using it)*: Postcondition assertion predicate.

**Return Value / Type:** `void`

## Paired Keywords & Related Topics
`require`, `contract`, `header`, `outbound`, `it`

## Runnable Code Example
```verscript
def func abs(x: num):
  ensure: it >= 0
  if x < 0 then: reply -x else: reply x
```
