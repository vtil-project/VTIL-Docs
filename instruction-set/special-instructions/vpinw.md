---
description: Pins a register for write and prevents optimization across that write dependency.
---

# VPINW

| Instruction | Operand 1 | Description |
| :--- | :--- | :--- |
| VPINW | Reg | Pins the register for write |

```cpp
block->vpinw(X86_REG_AL);
```

