# send — Transmit Message to Channel

> **Category**: `keyword` | **Subcategory**: Concurrency & Reactive

## Overview
Pushes a message onto a concurrency channel. Blocks if the channel buffer is saturated.

## Syntax
```verscript
send <channel>, <message>
```

## Example
```verscript
set queue : chan 2
send queue, 100
send queue, 200
```

