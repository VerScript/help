# when — Reactive Conditional Observer

> **Category**: `keyword` | **Subcategory**: Reactive & Event Architecture

## Overview
Monitors a reactive property or state expression, executing a reaction as soon as the condition transitions to true.

## Syntax
```verscript
when <condition>:
  <reactive_action>
```

## Example
```verscript
set fuelLevel : 10
when fuelLevel < 15:
  display "LOW FUEL: Refuel required immediately." ?color=#f59e0b
```

