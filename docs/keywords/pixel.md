# pixel — Direct Framebuffer Pixel Access

**Category:** Framebuffer Manipulation  
**Identifier:** `pixel`

---

## Summary
Sets or retrieves raw RGBA pixel color at $(x, y)$ coordinate on the active surface.

## Syntax
```verscript
pixel(x, y) : color
```

**Parameters:** x (int), y (int), color (hex / uint32)  
**Returns:** Reads or writes pixel  
**Paired Keywords:** `screen, draw`

## Code Example
```verscript
screen.pixel(400, 300) : #00FFCC
```

---
*Part of the official VerScript Language Reference.*
