---
description: Pins a register for write. This prevents optimization to optimize through it.
---

# VPINW

| Instruction | Operand 1 | Description |
| :--- | :--- | :--- |
| VPINW | Reg | Pins the register for write |

```cpp
block->vpinw(X86_REG_AL);
```

