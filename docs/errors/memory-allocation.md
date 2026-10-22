# MemoryAllocationError — Allocation Failure

> **Category**: `error` | **Subcategory**: Runtime & Memory

## Overview
Raised when the operating system or native allocator refuses memory requests due to heap exhaustion or bounds violations.

## Criticality & Suppression
- **Criticality Score**: 9 / 10
- **Suppression Tier**: Tier 4 (Unsuppressable Fatal)

### Common Trigger
Requested buffer exceeds available physical RAM; infinite recursive allocation loops.

### Recommended Remedy
Check array bounds, verify recursion termination conditions, and free tracked references.

## Example
```verscript
do:
  ! Allocate safe size
  set safeArr : [1, 2, 3, 4]
unless MemoryAllocationError:
  display "System low on memory; terminating buffers." ?color=#ef4444
```

