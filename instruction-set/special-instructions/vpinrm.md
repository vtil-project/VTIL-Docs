---
description: >-
  Pins the address specified in a register and offset for read. This prevents
  optimization to optimize through it.
---

# VPINRM

| Instruction | Operand 1 | Operand 2 | Description |
| :--- | :--- | :--- | :--- |
| VPINRM | Reg | Imm | Pins the qword @ memory location for read |

```cpp
block->vpinrm(REG_SP, 3ull);
```

