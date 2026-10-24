# conj — Complex Conjugate

**Category:** Complex Number Operation  
**Identifier:** `conj`

---

## Summary
Computes the complex conjugate of $a + bi$, returning $a - bi$.

## Syntax
```verscript
conj(complex_val)
```

**Parameters:** complex_val (complex)  
**Returns:** complex number ($a - bi$)  
**Paired Keywords:** `complex, real, imag`

## Code Example
```verscript
z : complex(3, 4)
z_star : conj(z)
display "Conjugate: " + z_star  ! 3 - 4i
```

---
*Part of the official VerScript Language Reference.*
