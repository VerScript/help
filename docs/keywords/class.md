# class — Object-Oriented Blueprint

> **Category**: `keyword` | **Subcategory**: Object-Oriented Architecture

## Overview
Declares an object-oriented class with encapsulated fields, static properties, constructors, and instance methods.

## Syntax
```verscript
class <ClassName>:
  [static: ...]
  [dynamic: ...]
  def init(args):
    ...
```

## Example
```verscript
class BankAccount:
  def init(holder, balance):
    set this.holder : holder
    set this.balance : balance
  def deposit(amt):
    set this.balance : this.balance + amt
    reply this.balance
```

