# async

**Category:** KEYWORD | **Subcategory:** Concurrency & Reactive

## Summary
Spawns an asynchronous concurrent worker thread or fiber, executing the block non-blockingly.

## Syntax
```verscript
async:
  <body>

set task : async def taskName():
  <body>
```

## Parameters / Arguments
- `block` *(statement block)*: undefined

## Runnable Code Example
```verscript
set ch : chan 5
async:
  send ch, "Hello from fiber!"
set msg : recv ch
display "Received: " + msg ?color=#00FFCC
```
