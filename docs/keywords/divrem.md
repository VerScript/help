# divRem / divrem — Combined Division and Remainder

**Category:** Arithmetic Operation  
**Identifier:** `divRem`

---

## Summary
Computes integer quotient and remainder simultaneously, returning a two-element tuple `[quotient, remainder]`.

## Syntax
```verscript
divRem(numerator, denominator)
```

**Parameters:** numerator (int), denominator (int)  
**Returns:** arr [quotient, remainder]  
**Paired Keywords:** `//, %`

## Code Example
```verscript
res : divRem(17, 5)
display "Quotient: " + res[0] + ", Remainder: " + res[1]
```

---
*Part of the official VerScript Language Reference.*
