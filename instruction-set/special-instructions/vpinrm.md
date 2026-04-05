---
description: >-
  Pins a memory location for read using base register, displacement, and size,
  and prevents optimization across that memory read dependency.
---

# VPINRM

| Instruction | Operand 1 | Operand 2 | Operand 3 | Description |
| :--- | :--- | :--- | :--- | :--- |
| VPINRM | Reg | Imm | Imm | Pins the memory location for read, with size = Operand 3 |

```cpp
block->vpinrm(REG_SP, 3ull, 64);
```

