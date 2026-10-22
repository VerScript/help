# arr

**Category:** DATATYPE | **Subcategory:** Collections

## Summary
Dynamically sized heterogeneous linear collection supporting indexed access, push/pop, and slice operations.

## Syntax
```verscript
set arr <name> : [<elem1>, <elem2>, ...]
set <elem> : <name>[<index>]
```

## Description
Arrays hold an ordered list of elements of any type. They support indexing with zero-based integer offsets, length querying with `arr.length`, functional pipelines, and iteration loops.

## Parameters / Arguments
- `elements` *(comma-separated values)*: Elements enclosed within square brackets [].

**Return Value / Type:** `arr`

## Paired Keywords & Related Topics
`cycle`, `loop`, `iterate`, `Array`, `in`

## Runnable Code Example
```verscript
set arr items : [1, "two", 3.0, true]
items.push(50)
display "Length: " + items.length
display items[1]
```
