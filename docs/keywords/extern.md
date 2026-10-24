# extern — Dynamic Win32 / Native Shared Library FFI

**Category:** Foreign Function Interface  
**Identifier:** `extern`

---

## Summary
Declares and binds external dynamic symbols from system DLLs (e.g. kernel32.dll) for direct runtime invocation.

## Syntax
```verscript
extern "library.dll" function_name(args)
```

**Parameters:** library.dll (string), function_name (identifier)  
**Returns:** Native integer or pointer return value  
**Paired Keywords:** `def, func, load`

## Code Example
```verscript
extern "kernel32.dll" GetCurrentProcessId()
pid : GetCurrentProcessId()
display "Native Win32 Process ID: " + pid ?color=#00FFCC
```

---
*Part of the official VerScript Language Reference.*
