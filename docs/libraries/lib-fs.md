# Fs

**Category:** LIBRARY | **Subcategory:** Standard Library (System)

## Summary
Synchronous and asynchronous file I/O: reading text/binary files, writing files, directory traversal, and path checking.

## Syntax
```verscript
load Fs
Fs.read(path)
Fs.write(path, data)
Fs.exists(path)
Fs.list(dirPath)
```

## Parameters / Arguments
- `path` *(str)*: undefined
- `data` *(str)*: undefined

## Runnable Code Example
```verscript
load Fs
if Fs.exists("config.json") then
  set cfg : Fs.read("config.json")
  display "Loaded config." ?color=#00FFCC
```
