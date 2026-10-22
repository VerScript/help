# inject — In-Line Polyglot Code Injection

> **Category**: `keyword` | **Subcategory**: Polyglot & Metaprogramming

## Overview
Executes embedded foreign language code directly within VerScript, with automatic cross-runtime variable marshalling.

## Syntax
```verscript
inject <language>:
  <foreign code block>
```

## Example
```verscript
inject js:
  const now = new Date().toISOString();
  console.log("Current ISO timestamp:", now);
```

