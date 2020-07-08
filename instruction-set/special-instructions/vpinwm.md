---
description: >-
  Pins the address specified in a register and offset for write. This prevents
  optimization to optimize through it.
---

# VPINWM

| Instruction | Operand 1 | Operand 2 | Description |
| :--- | :--- | :--- | :--- |
| VPINWM | Reg | Imm | Pins the qword @ memory location for write |

```cpp
block->vpinwm(REG_SP, 3ull);
```

