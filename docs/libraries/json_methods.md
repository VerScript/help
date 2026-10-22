# Json.parse / Json.stringify

**Category:** LIBRARY | **Subcategory:** Serialization

## Summary
Parses JSON text into VerScript entities and arrays, or serializes data into formatted JSON strings.

## Syntax
```verscript
load Json
set data : Json.parse(jsonString)
set text : Json.stringify(data)
```

## Description
Standard JSON parser and serializer with support for nested arrays, dictionaries, numbers, and escape characters.

## Parameters / Arguments
- `input` *(str or entity)*: JSON string to parse, or entity to serialize.

**Return Value / Type:** `entity | arr | str`

## Paired Keywords & Related Topics
`load`, `Fs`, `Http`, `str`

## Runnable Code Example
```verscript
load Json
set obj : Json.parse('{"name": "VerScript", "version": 2}')
display obj.name
```
