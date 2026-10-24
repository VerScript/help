# flush — Flush Output Buffers

**Category:** I/O Control  
**Identifier:** `flush`

---

## Summary
Forces all pending output stream buffers to be written immediately to the console or file.

## Syntax
```verscript
flush() or stream.flush()
```

**Parameters:** None or stream target  
**Returns:** None  
**Paired Keywords:** `display, terminal`

## Code Example
```verscript
display "Computing..." ?inline=true
flush()
```

---
*Part of the official VerScript Language Reference.*
