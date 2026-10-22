# async — Asynchronous Task Execution

> **Category**: `keyword` | **Subcategory**: Concurrency & Reactive

## Overview
Spawns an asynchronous concurrent worker thread or fiber, executing the block non-blockingly.

## Syntax
```verscript
async:
  <body>

set task : async def taskName():
  <body>
```

## Example
```verscript
set ch : chan 5
async:
  send ch, "Hello from fiber!"
set msg : recv ch
display "Received: " + msg ?color=#00FFCC
```

