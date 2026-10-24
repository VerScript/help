# frame — Render Frame Clock & Delta Time

**Category:** Animation & Delta Time  
**Identifier:** `frame`

---

## Summary
Provides timing context and delta time ($Delta t$) within game loops and animation callbacks.

## Syntax
```verscript
on frame(delta):
    ...
```

**Parameters:** delta (num elapsed seconds)  
**Returns:** Frame execution context  
**Paired Keywords:** `on, loop, render`

## Code Example
```verscript
on frame(dt):
    player.x : player.x + (speed * dt)
```

---
*Part of the official VerScript Language Reference.*
