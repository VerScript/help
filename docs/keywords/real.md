# real — Extract Real Component

**Category:** Complex Number Component  
**Identifier:** `real`

---

## Summary
Extracts the real component from a complex number instance.

## Syntax
```verscript
real(complex_val) or complex_val.real
```

**Parameters:** complex_val (complex)  
**Returns:** num (real part)  
**Paired Keywords:** `imag, complex`

## Code Example
```verscript
z : complex(5, -2)
display "Real: " + real(z)  ! Outputs 5
```

---
*Part of the official VerScript Language Reference.*
