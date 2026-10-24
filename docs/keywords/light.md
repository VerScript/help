# light — Illumination Source Descriptor

**Category:** Scene Illumination  
**Identifier:** `light`

---

## Summary
Adds ambient, directional, or point lighting to a 3D scene.

## Syntax
```verscript
light(type, color, intensity)
```

**Parameters:** type ("ambient" | "point" | "sun"), color (hex), intensity (num)  
**Returns:** light instance  
**Paired Keywords:** `scene, world, render`

## Code Example
```verscript
sun : light("sun", #FFFFFF, 1.2)
```

---
*Part of the official VerScript Language Reference.*
