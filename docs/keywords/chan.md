# chan — CSP Concurrency Channel

> **Category**: `keyword` | **Subcategory**: Concurrency & Reactive

## Overview
Creates a typed or buffered Communicating Sequential Processes (CSP) channel for thread-safe message passing.

## Syntax
```verscript
set <ch> : chan [bufferSize]
```

## Example
```verscript
set messages : chan 3
send messages, "MSG_1"
send messages, "MSG_2"
display recv messages ?color=#00FFCC
display recv messages ?color=#38bdf8
```

