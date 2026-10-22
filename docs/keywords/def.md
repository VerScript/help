# def — General Procedure and Method Definition

> **Category**: `keyword` | **Subcategory**: Procedures & Functions

## Overview
Declares a callable procedure or function block. Can have side effects, accept arguments, and return values with reply.

## Syntax
```verscript
def <name> ( [arg1, arg2, ...] ):
  <body>
  reply <value>
```

## Example
```verscript
def greet(name, role):
  display "Operator: " + name + " [" + role + "]" ?color=#38bdf8
  reply true

greet("Dr. Aris", "Lead Scientist")
```

