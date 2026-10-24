# close — Close Stream, Channel, or Session

**Category:** Resource Lifecycle  
**Identifier:** `close`

---

## Summary
Closes an active file handle, network socket, concurrency channel, or terminal session.

## Syntax
```verscript
close(handle)
```

**Parameters:** handle (channel, file, or socket)  
**Returns:** None  
**Paired Keywords:** `chan, load`

## Code Example
```verscript
ch : chan<num>(5)
close(ch)
```

---
*Part of the official VerScript Language Reference.*
