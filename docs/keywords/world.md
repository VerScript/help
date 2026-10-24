# world — 3D Spatial Container & Physics Environment

**Category:** Spatial Environment  
**Identifier:** `world`

---

## Summary
Defines the 3D spatial simulation coordinate space and physics world settings.

## Syntax
```verscript
world(gravity, bounds)
```

**Parameters:** gravity (vector), bounds (box)  
**Returns:** world container object  
**Paired Keywords:** `spawn, scene, light`

## Code Example
```verscript
simWorld : world([0, -9.8, 0])
```

---
*Part of the official VerScript Language Reference.*
