# How to Run Background Fibers and Message Passing

> **Category**: `functionality` | **Subcategory**: Concurrency

## Overview
Spawning concurrent non-blocking workers with 'async' and passing messages through thread-safe 'chan', 'send', and 'recv'.

## Example
```verscript
set queue : chan 2
async:
  Time.sleep(500)
  send queue, "Worker finished payload"

set msg : recv queue
display "Master received: " + msg ?color=#00FFCC
```

