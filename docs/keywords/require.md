# require

**Category:** KEYWORD | **Subcategory:** Header Contracts

## Summary
Specifies a precondition predicate that must evaluate to true prior to executing a routine.

## Syntax
```verscript
require: <boolean_condition>
```

## Description
If the `require` predicate evaluates to false or 0 upon entering a routine, the runtime immediately throws a `PreconditionViolationError`.

## Parameters / Arguments
- `condition` *(bool)*: Precondition assertion expression.

**Return Value / Type:** `void`

## Paired Keywords & Related Topics
`ensure`, `contract`, `header`, `inbound`

## Runnable Code Example
```verscript
def func withdraw(amount: num):
  require: amount > 0 && amount <= this.balance
  set this.balance : this.balance - amount
```
