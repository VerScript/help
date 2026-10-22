# construct

**Category:** KEYWORD | **Subcategory:** Object Orientation

## Summary
Constructor block or routine automatically invoked when instantiating a class or library entity.

## Syntax
```verscript
class <Name> <arg1> <arg2>:
  construct:
    set this.<field1> : <arg1>
    set this.<field2> : <arg2>

lib <LibName> <arg1>:
  construct:
    ...
```

## Description
The constructor initializes an entity's dynamic state upon creation. Parameters passed into `MyClass(a, b)` or `MyLib(a, b)` are bound in scope and available to initialize `this` properties. Constructors require no arguments of their own because class/lib arguments are attached directly to the definition.

## Parameters / Arguments
- `this properties` *(assignments)*: Initialization statements setting this.<prop> fields.

**Return Value / Type:** `Entity Instance`

## Paired Keywords & Related Topics
`class`, `lib`, `this`, `inst`, `set`

## Runnable Code Example
```verscript
class Vector2D x y:
  construct:
    set this.x : x
    set this.y : y
  def func magnitude:
    reply Math.sqrt(this.x * this.x + this.y * this.y)

set v : Vector2D(3, 4)
display v.magnitude()  ! 5
```
