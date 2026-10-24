# yield — Generator Value Suspension

**Category:** Coroutine Generator  
**Identifier:** `yield`

---

## Summary
Suspends function execution and yields an intermediate value to the consumer.

## Syntax
```verscript
yield value
```

**Parameters:** value (any)  
**Returns:** Yielded element  
**Paired Keywords:** `func, reply, async`

## Code Example
```verscript
func countUp(max):
    for i in 1 .. max:
        yield i
```

---
*Part of the official VerScript Language Reference.*
