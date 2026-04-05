---
description: VTIL memory-read fence that assumes all memory is read from.
---

# SFENCE

| Instruction | Description |
| :--- | :--- |
| SFENCE | Assumes all memory is read from |

Note: In VTIL, `SFENCE` is a symbolic memory-read fence.

```cpp
block->sfence();
```