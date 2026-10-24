# split — Split Panes or Delimited Strings

**Category:** Layout & Text Splitting  
**Identifier:** `split`

---

## Summary
Dual-purpose keyword: splits strings by a delimiter or splits terminal viewports into tiled panes.

## Syntax
```verscript
str.split(delim) or terminal.split(direction)
```

**Parameters:** delim (str) or direction ("horizontal" | "vertical")  
**Returns:** arr of strings or new pane handle  
**Paired Keywords:** `join, terminal`

## Code Example
```verscript
words : "apple,banana,orange".split(",")
display words[0]
```

---
*Part of the official VerScript Language Reference.*
