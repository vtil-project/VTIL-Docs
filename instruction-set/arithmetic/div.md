---
description: >-
  Performs an unsigned division on a register with a register or immediate
  value. The dividend is represented by 2 registers for high and low bits.
---

# DIV

| Instruction | Operand 1 | Operand 2 | Operand 3 | Description |
| :--- | :--- | :--- | :--- | :--- |
| DIV | Reg | Reg/Imm | Reg/Imm | OP1 = \[OP2:OP1\] / OP3 |

```cpp
block->div(REG_SP, 0, REG_SP); // sets REG_SP to 1
```



