# entity

**Category:** DATATYPE | **Subcategory:** Object Orientation

## Summary
Dynamic object record or instantiated class/library instance holding bound methods and member fields.

## Syntax
```verscript
set entity <name> : <ClassOrLibName>(<args...>)
set <name>.<prop> : <val>
```

## Description
Entities represent stateful object instances. They can be created from `class` blueprints, `lib` modules with constructors, or dynamic property maps. Entity members are accessed via the dot `.` operator.

## Parameters / Arguments
- `constructor` *(Class or Lib invocation)*: Invocation of a class or library with constructor parameters.

**Return Value / Type:** `entity`

## Paired Keywords & Related Topics
`class`, `lib`, `construct`, `this`, `inst`

## Runnable Code Example
```verscript
class Point x y:
  construct:
    set this.x : x
    set this.y : y

set p : Point(10, 20)
display p.x + ", " + p.y
```
