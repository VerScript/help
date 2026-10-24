# camera — Viewport Projection & Camera Controller

**Category:** Camera & Projection  
**Identifier:** `camera`

---

## Summary
Constructs and positions a virtual perspective or orthographic camera.

## Syntax
```verscript
camera(fov, aspect, near, far)
```

**Parameters:** fov (field of view in degrees), aspect (aspect ratio)  
**Returns:** camera controller instance  
**Paired Keywords:** `render, scene`

## Code Example
```verscript
cam : camera(60, 16/9, 0.1, 1000)
cam.position : [0, 5, 10]
```

---
*Part of the official VerScript Language Reference.*
