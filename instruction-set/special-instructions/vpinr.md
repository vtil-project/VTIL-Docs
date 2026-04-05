---
description: Pins a register for read and prevents optimization across that read dependency.
---

# VPINR

| Instruction | Operand 1 | Description |
| :--- | :--- | :--- |
| VPINR | Reg | Pins the register for read |

```cpp
block->vpinr(X86_REG_AL);
```

