# Fs — File System Operations

> **Category**: `library` | **Subcategory**: Standard Library (System)

## Overview
Synchronous and asynchronous file I/O: reading text/binary files, writing files, directory traversal, and path checking.

## Syntax
```verscript
load Fs
Fs.read(path)
Fs.write(path, data)
Fs.exists(path)
Fs.list(dirPath)
```

## Example
```verscript
load Fs
if Fs.exists("config.json") then
  set cfg : Fs.read("config.json")
  display "Loaded config." ?color=#00FFCC
```

