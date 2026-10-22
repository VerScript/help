# MemoryAllocationError

**Category:** ERROR | **Subcategory:** Runtime & Memory

## Summary
Raised when the operating system or native allocator refuses memory requests due to heap exhaustion or bounds violations.

## Syntax
```verscript
undefined
```

## Runnable Code Example
```verscript
do:
  ! Allocate safe size
  set safeArr : [1, 2, 3, 4]
unless MemoryAllocationError:
  display "System low on memory; terminating buffers." ?color=#ef4444
```
