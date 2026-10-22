# load

**Category:** KEYWORD | **Subcategory:** Module & Library System

## Summary
Loads one or more VerScript standard libraries into the execution environment. Supports comma-separated multi-loading.

## Syntax
```verscript
load <Library1> [, <Library2>, ...]
```

## Parameters / Arguments
- `libraries` *(identifiers...)*: undefined

## Runnable Code Example
```verscript
load Crypto, Json
set payload : Json.stringify({ user: "alex", role: "admin" })
set hash : Crypto.sha256(payload)
display "Payload Hash: " + hash ?color=#00FFCC
```
