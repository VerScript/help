# Watchdog

**Category:** LIBRARY | **Subcategory:** Standard Library

## Summary
Hardware memory and execution time watchdogs preventing freeze and leaks.

## Syntax
```verscript
load Watchdog
Watchdog.arm(maxMs)
Watchdog.feed()
```

## Runnable Code Example
```verscript
load Watchdog
Watchdog.arm(maxMs)
Watchdog.feed()
display "Library initialized." ?color=#00FFCC
```
