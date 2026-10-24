# lerp — Linear Interpolation

**Category:** Interpolation Function  
**Identifier:** `lerp`

---

## Summary
Calculates the linear interpolation between point a and point b for parameter t ($a + (b - a) 	imes t$).

## Syntax
```verscript
lerp(start, end, t)
```

**Parameters:** start (num), end (num), t (num from 0.0 to 1.0)  
**Returns:** num (interpolated value)  
**Paired Keywords:** `clamp`

## Code Example
```verscript
mid : lerp(0, 100, 0.5)
display "Midpoint: " + mid  ! Outputs 50
```

---
*Part of the official VerScript Language Reference.*
