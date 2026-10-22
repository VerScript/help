# inject

**Category:** KEYWORD | **Subcategory:** Polyglot & Metaprogramming

## Summary
Executes embedded foreign language code directly within VerScript, with automatic cross-runtime variable marshalling.

## Syntax
```verscript
inject <language>:
  <foreign code block>
```

## Parameters / Arguments
- `language` *(identifier)*: undefined
- `code block` *(indented block)*: undefined

## Runnable Code Example
```verscript
inject js:
  const now = new Date().toISOString();
  console.log("Current ISO timestamp:", now);
```
