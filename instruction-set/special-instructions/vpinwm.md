---
description: >-
  Pins a memory location for write using base register, displacement, and size,
  and prevents optimization across that memory write dependency.
---

# VPINWM

| Instruction | Operand 1 | Operand 2 | Operand 3 | Description |
| :--- | :--- | :--- | :--- | :--- |
| VPINWM | Reg | Imm | Imm | Pins the memory location for write, with size = Operand 3 |

```cpp
block->vpinwm(REG_SP, 3ull, 64);
```

