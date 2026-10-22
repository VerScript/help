# prompt

**Category:** KEYWORD | **Subcategory:** I/O & Concurrency

## Summary
Suspends execution to receive interactive user input from stdin, terminal, or IDE interactive runbox.

## Syntax
```verscript
set <var> : prompt ["Optional Question String"]
```

## Parameters / Arguments
- `message (optional)` *(string)*: undefined

## Runnable Code Example
```verscript
set command : prompt "vrs> "
if command == "exit" then
  display "Exiting session." ?color=#ef4444
else
  display "Executing: " + command ?color=#00FFCC
end
```
