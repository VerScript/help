# scene — Scene Graph Container

**Category:** Scene Graph  
**Identifier:** `scene`

---

## Summary
Container managing all entities, lights, meshes, and cameras for a visual frame.

## Syntax
```verscript
scene() or scene.add(entity)
```

**Parameters:** None or entity list  
**Returns:** scene graph object  
**Paired Keywords:** `render, world, camera`

## Code Example
```verscript
lvl : scene()
lvl.add(sun)
lvl.add(player)
```

---
*Part of the official VerScript Language Reference.*
