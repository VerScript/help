# Json — JSON Serialization and Parsing

> **Category**: `library` | **Subcategory**: Standard Library (Data)

## Overview
Converts VerScript arrays and entity objects to standard JSON strings, and parses JSON strings into native data structures.

## Syntax
```verscript
load Json
Json.stringify(obj [, pretty])
Json.parse(jsonString)
```

## Example
```verscript
load Json
set user : { id: 1, name: "Ada Lovelace", verified: true }
set jsonStr : Json.stringify(user)
display jsonStr ?color=#00FFCC
```

