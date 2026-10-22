# send

**Category:** KEYWORD | **Subcategory:** Concurrency & Reactive

## Summary
Pushes a message onto a concurrency channel. Blocks if the channel buffer is saturated.

## Syntax
```verscript
send <channel>, <message>
```

## Parameters / Arguments
- `channel` *(chan)*: undefined
- `message` *(any)*: undefined

## Runnable Code Example
```verscript
set queue : chan 2
send queue, 100
send queue, 200
```
