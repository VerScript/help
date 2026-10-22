# Fs.readFile / Fs.writeFile

**Category:** LIBRARY | **Subcategory:** Filesystem

## Summary
Reads, writes, and manages files and directories on the local host filesystem.

## Syntax
```verscript
load Fs
set content : Fs.readFile("data.txt")
Fs.writeFile("output.txt", content)
Fs.exists("data.txt")
```

## Description
Provides direct filesystem access. Automatically handles file descriptors, binary buffers, and text encodings.

## Parameters / Arguments
- `path` *(str)*: Filesystem path.
- `content` *(str)*: Data to write.

**Return Value / Type:** `str or bool`

## Paired Keywords & Related Topics
`load`, `Path`, `Sys`

## Runnable Code Example
```verscript
load Fs
if Fs.exists("config.vrs") then:
  set cfg : Fs.readFile("config.vrs")
```
