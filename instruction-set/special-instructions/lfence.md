---
description: VTIL memory-write fence that assumes all memory is written to.
---

# LFENCE

| Instruction | Description |
| :--- | :--- |
| LFENCE | Assumes all memory is written to |

Note: In VTIL, `LFENCE` is a symbolic memory-write fence.

```cpp
block->lfence();
```