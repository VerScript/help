# recv

**Category:** KEYWORD | **Subcategory:** Concurrency & Reactive

## Summary
Pulls and consumes the next available message from a channel. Blocks if the channel is currently empty.

## Syntax
```verscript
set <msg> : recv <channel>
```

## Parameters / Arguments
- `channel` *(chan)*: undefined

## Runnable Code Example
```verscript
set pipe : chan 1
send pipe, "Ping"
set reply : recv pipe
display reply ?color=#00FFCC
```
