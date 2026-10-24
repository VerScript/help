# imag — Extract Imaginary Component

**Category:** Complex Number Component  
**Identifier:** `imag`

---

## Summary
Extracts the imaginary component coefficient from a complex number instance.

## Syntax
```verscript
imag(complex_val) or complex_val.imag
```

**Parameters:** complex_val (complex)  
**Returns:** num (imaginary part)  
**Paired Keywords:** `real, complex`

## Code Example
```verscript
z : complex(5, -2)
display "Imag: " + imag(z)  ! Outputs -2
```

---
*Part of the official VerScript Language Reference.*
