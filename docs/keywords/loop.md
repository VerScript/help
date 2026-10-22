# loop — Universal Iteration Engine

> **Category**: `keyword` | **Subcategory**: Iteration & Control Flow

## Overview
Primary iteration construct in VerScript. Supports range iteration (from...to), step quantifiers (by), collection iteration, and fixed repeats.

## Syntax
```verscript
loop [var] from <start> to <end> [by <step>]:
  <body>

loop <item> in <collection>:
  <body>

loop <count>:
  <body>
```

## Example
```verscript
set primes : []
loop num from 2 to 20:
  set isP : true
  loop d from 2 to (num - 1):
    if num % d == 0 then set isP : false
  if isP then primes.push(num)
display "Primes: " + primes ?color=#00FFCC
```

