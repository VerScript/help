# display

**Category:** KEYWORD | **Subcategory:** I/O & Concurrency

## Summary
Streams evaluated arguments to standard output. Supports ANSI Truecolor hex styling, inline printing, formatting tags, and multiple arguments.

## Syntax
```verscript
display <expr1> [, <expr2>, ...] [?<attribute>=<value>]
```

## Parameters / Arguments
- `expressions` *(any...)*: undefined
- `?color` *(attribute (hex/name))*: undefined
- `?inline` *(attribute flag)*: undefined

## Runnable Code Example
```verscript
display "=== System Telemetry ===" ?color=#bd00ff
display "Uptime: 99.98%" ?color=#00FFCC
display "Load Avg: 0.12" ?color=#38bdf8
```
