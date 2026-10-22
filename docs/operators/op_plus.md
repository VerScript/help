# + (Addition / Concat)

**Category:** OPERATOR | **Subcategory:** Arithmetic & Strings

## Summary
Adds numeric values, concatenates strings, or appends elements to arrays.

## Syntax
```verscript
<a> + <b>
```

## Description
Polymorphic operator: (1) Numeric addition: 5 + 3 = 8, (2) String concatenation: "Hello " + "World", (3) Array union: [1, 2] + [3, 4].

## Parameters / Arguments
- `a` *(num | str | arr)*: Left operand.
- `b` *(num | str | arr)*: Right operand.

**Return Value / Type:** `num | str | arr`

## Paired Keywords & Related Topics
`-`, `*`, `/`, `%`

## Runnable Code Example
```verscript
set n : 10 + 25
set msg : "Total count: " + n
display msg
```
