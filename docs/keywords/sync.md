# sync — Synchronous Block Execution

**Category:** Concurrency & Synchronization  
**Identifier:** `sync`

---

## Summary
Blocks and synchronizes execution until an async task, promise, or channel completes.

## Syntax
```verscript
sync:
  action()
```

**Parameters:** None  
**Returns:** Blocks until completion  
**Paired Keywords:** `async, chan, emit`

## Code Example
```verscript
sync:
    display "Synchronous critical section"
```

---
*Part of the official VerScript Language Reference.*
