# ? (Directive / Flag Marker)

**Category:** OPERATOR | **Subcategory:** Directives & Flags

## Summary
Prefixes modifier flags and inline parameters on statements (e.g. ?color=cyan, ?default=25, ?override).

## Syntax
```verscript
display <msg> ?color=<name> ?bold
prompt <var> ?default=<val>
```

## Description
VerScript statements support inline keyword options prefixed by `?` to configure visual formatting or execution flags.

**Return Value / Type:** `void`

## Paired Keywords & Related Topics
`display`, `prompt`, `meta`, `pragma`

## Runnable Code Example
```verscript
display "Success!" ?color=green ?bold
prompt username ?default="Guest"
```
