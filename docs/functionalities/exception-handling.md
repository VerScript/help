# How to Catch and Shield Exceptions in VerScript

> **Category**: `functionality` | **Subcategory**: Control Flow

## Overview
Using the 'do...unless' block architecture to intercept runtime errors, prevent crashes, and implement graceful recovery fallbacks.

## Example
```verscript
do:
  set result : riskyCalculation()
unless DivisionByZeroError:
  display "Caught division by zero; setting default." ?color=#f59e0b
  set result : 0
unless:
  display "Caught unexpected error." ?color=#ef4444
  set result : null
```

