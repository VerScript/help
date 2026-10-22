# prompt — Interactive User Input

> **Category**: `keyword` | **Subcategory**: I/O & Concurrency

## Overview
Suspends execution to receive interactive user input from stdin, terminal, or IDE interactive runbox.

## Syntax
```verscript
set <var> : prompt ["Optional Question String"]
```

## Example
```verscript
set command : prompt "vrs> "
if command == "exit" then
  display "Exiting session." ?color=#ef4444
else
  display "Executing: " + command ?color=#00FFCC
end
```

