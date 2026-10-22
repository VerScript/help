# Watchdog — Standard Library

> **Category**: `library` | **Subcategory**: Standard Library

## Overview
Hardware memory and execution time watchdogs preventing freeze and leaks.

## Syntax
```verscript
load Watchdog
Watchdog.arm(maxMs)
Watchdog.feed()
```

## Example
```verscript
load Watchdog
Watchdog.arm(maxMs)
Watchdog.feed()
display "Library initialized." ?color=#00FFCC
```

