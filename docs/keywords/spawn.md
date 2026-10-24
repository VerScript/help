# spawn — Instantiate Scene Entity

**Category:** Entity Instantiation  
**Identifier:** `spawn`

---

## Summary
Spawns a game object, actor, or geometry mesh into the active scene hierarchy.

## Syntax
```verscript
spawn entity at position
```

**Parameters:** entity (object), position (vector)  
**Returns:** spawned instance handle  
**Paired Keywords:** `world, scene, inst`

## Code Example
```verscript
player : spawn Entity("Hero") at [0, 0, 0]
```

---
*Part of the official VerScript Language Reference.*
