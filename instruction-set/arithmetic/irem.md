---
description: >-
  Performs a signed modulo operation on a register with a register or immediate
  value. The source value is represented by 2 registers for high and low bits.
---

# IREM

| Instruction | Operand 1 | Operand 2 | Operand 3 | Description |
| :--- | :--- | :--- | :--- | :--- |
| IREM | Reg | Reg/Imm | Reg/Imm | OP1 = \[OP2:OP1\] % OP3 \(Signed\) |

```cpp
block->irem(REG_SP, 0, REG_SP); // sets REG_SP to 0
```

