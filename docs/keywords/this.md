# this

**Category:** KEYWORD | **Subcategory:** Object Orientation

## Summary
Implicit reference to the current entity instance executing a method or constructor.

## Syntax
```verscript
this.<property>
this.<method>()
```

## Description
Within `class` and `lib` methods and constructors, `this` binds to the active instance state and dynamic member variables.

**Return Value / Type:** `entity`

## Paired Keywords & Related Topics
`class`, `lib`, `construct`, `thisstatic`

## Runnable Code Example
```verscript
class Counter:
  construct:
    set this.val : 0
  def func inc:
    set this.val : this.val + 1
```
